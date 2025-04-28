# 🌊 Flood Area Segmentation - Bootcamp de Machine Learning | Atlântico Avanti

Projeto desenvolvido em equipe durante o **Bootcamp de Machine Learning** promovido pela **Atlântico Avanti**. Nosso desafio consiste em aplicar técnicas de Visão Computacional e Aprendizado de Máquina para **segmentar áreas afetadas por inundações** a partir de imagens de satélite.

## 📁 Dataset

Utilizamos o dataset disponível no Kaggle:  
🔗 [Flood Area Segmentation Dataset](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation/data)

O conjunto de dados contém:
- Imagens das áreas inundadas
- Máscaras de segmentação que identificam áreas inundadas

## 🎯 Objetivo

Construir um modelo de **segmentação semântica** capaz de identificar com precisão as regiões alagadas em imagens de satélite.  
Esse tipo de solução pode ser aplicada para monitoramento ambiental, resposta a desastres naturais e planejamento urbano.

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3.9+
- **Bibliotecas principais:**  
  - NumPy / Pandas
  - Matplotlib / Seaborn
  - OpenCV
  - TensorFlow / Keras
- **Modelos testados:**
  - ERFNet
  - UNet adaptada com EfficientNetB2
- **Ambiente:** Google Colab / Jupyter Notebook

## 🧪 Etapas do Projeto

1. **Análise Exploratória dos Dados (EDA)**  
   - Visualização de imagens e máscaras  
   - Verificação de balanceamento de classes  
   - Estatísticas básicas dos dados  

2. **Pré-processamento**  
   - Redimensionamento das imagens  
   - Normalização dos pixels  
   - Augmentations (data augmentation) para aumentar a robustez do modelo  

3. **Treinamento dos Modelos**  
   - Arquitetura base: UNet  
   - Funções de perda customizadas (como Dice Loss)  
   - Métricas: IoU (Intersection over Union), F1 Score  

4. **Avaliação**  
   - Análise quantitativa e qualitativa  
   - Visualização das predições versus máscaras reais  

## 📊 Resultados (parciais)


## 🤝 Integrantes da Equipe

* [Adriana Bispo](https://www.linkedin.com/in/adrianabispo283/)

* [Alexandre Teixeira](https://www.linkedin.com/in/alexandre-teixeira-1544b8322/)

* [Anna Luiza Laudares](https://www.linkedin.com/in/anna-luiza-laudares-b0680b2b3/)

* [Gabriel Oliveira](linkedin.com/in/gabrieleight/)

* [Juliana Rodrigues](https://www.linkedin.com/in/julianarodriguess/)

* [Letícia Moreira](https://www.linkedin.com/in/let%C3%ADcia-moreira-pinto/)


## 🔍 Entregas
### Entrega 01:

Integridade dos Arquivos

1. Verificar se todas as imagens listadas no arquivo de informações realmente existem no diretório de imagens e vice-versa.
2. Verificar se todas as imagens estão no mesmo formato, ex: JPEG, PNG, etc.

Consistência dos Metadados

3. Verificar se há valores ausentes nos metadados e como esses casos são tratados.
4. Verificar valores inconsistentes, por exemplo: dimensões de imagens fora do esperado.

Qualidade das Imagens

5. Identificar imagens corrompidas que não podem ser abertas ou processadas.

Distribuição das Classes

6. Verificar a distribuição das classes para identificar possíveis desequilíbrios que possam afetar a modelagem

Duplicatas

7. Identificar imagens duplicadas que possam enviesar os resultados.
8. Verificar duplicatas no arquivo de informações.

### Entrega 03:
"Colocar etapas da entrega 03"