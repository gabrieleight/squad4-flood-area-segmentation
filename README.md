# Squad 4 - Flood Area Segmentation
# 🌊 Modelo de Segmentação de Áreas Inundadas

**Bootcamp Machine Learning - Atlântico Avanti**  
Repositório para desenvolvimento do projeto "Flood Area Segmentation" do bootcamp de Machine Learning da Atlântico Avanti

Projeto de análise exploratória e modelagem para identificação de áreas alagadas.

---

## 📋 Objetivo
Realizar análise exploratória do dataset [Flood Area Segmentation](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation), abordando:
- Verificação de formatos e integridade dos arquivos
- Processamento de imagens e máscaras
- Insights iniciais para construção de modelos de segmentação

---

## 🗂 Dataset
Disponível no Kaggle: [https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation?select=Image)  
Estrutura:
- Pasta `Image`: Imagens de áreas alagadas
- Pasta `Mask`: Máscaras de segmentação
- Arquivo `metadata.csv`: Metadados do conjunto de dados

---

## 👥 Equipe
* [Adriana Bispo](https://www.linkedin.com/in/adrianabispo283/)

* [Alexandre Teixeira](https://www.linkedin.com/in/alexandre-teixeira-1544b8322/)

* [Anna Luiza Laudares](https://www.linkedin.com/in/anna-luiza-laudares-b0680b2b3/)

* [Gabriel Oliveira](linkedin.com/in/gabrieleight/)

* [Juliana Rodrigues](https://www.linkedin.com/in/julianarodriguess/)

* [Letícia Moreira](https://www.linkedin.com/in/let%C3%ADcia-moreira-pinto/)

---

## 🔍 Entregas
- ### Entrega 01:
○​ Integridade dos Arquivos

1.​ Verifique se todas as imagens listadas no arquivo de informações realmente existem no diretório de imagens e vice-versa.
2.​ Verifique se todas as imagens estão no mesmo formato, ex: JPEG, PNG, etc.

○​ Consistência dos Metadados
1. Verifique se há valores ausentes nos metadados e como esses casos são tratados.
2.​ Verifique valores inconsistentes, por exemplo: dimensões de imagens fora do esperado.

○​ Qualidade das Imagens
1.​ Identifique imagens corrompidas que não podem ser abertas ou processadas.

○​ Distribuição das Classes
1.​ Verifique a distribuição das classes para identificar possíveis desequilíbrios que possam afetar a modelagem

○​ Duplicatas
1.​ Identifique imagens duplicadas que possam enviesar os resultados.
2.​ Verifique duplicatas no arquivo de informações.