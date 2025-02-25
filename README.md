# Dataset - Análise de Sentimentos em Comentários do Duolingo

Este repositório contém um conjunto de dados utilizado no estudo **"Avaliação Comparativa de Métodos de Processamento de Linguagem Natural na Análise de Sentimentos"**. O dataset foi extraído de comentários da Play Store sobre o aplicativo **Duolingo** e processado por diferentes abordagens de análise de sentimentos.

## Estrutura do CSV
O arquivo `dataset.csv` contém as seguintes colunas:

- **ID** → Identificação única do comentário.
- **Texto** → Comentário original do usuário.
- **Classificação Humana** → Rótulo atribuído manualmente (*Positivo, Negativo ou Neutro*).
- **Classificação TextBlob** → Resultado da análise usando a biblioteca TextBlob.
- **Classificação DeepSeek** → Resultado da análise pelo modelo DeepSeek.
- **Classificação ChatGPT** → Resultado da análise pelo modelo ChatGPT.

## Objetivo do Dataset
Este conjunto de dados foi criado para comparar a precisão de diferentes métodos de **Processamento de Linguagem Natural (PLN)** na análise de sentimentos. O estudo avalia métricas como **precisão, recall e F1-score**, destacando as diferenças entre abordagens léxicas e modelos baseados em aprendizado profundo.

## Como Usar
1. Baixe o arquivo CSV.
2. Utilize bibliotecas como **Pandas** para carregá-lo em Python:
   ```python
   import pandas as pd
   df = pd.read_csv('dataset.csv')
   print(df.head())
   ```

## Contato
Para dúvidas ou sugestões, entre em contato: **[rafaelbogo52@gmail.com](mailto:rafaelbogo52@gmail.com)**.
