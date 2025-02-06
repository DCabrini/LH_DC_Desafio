# LH_DC_Desafio

# Previsão de Preços de Aluguéis Temporários - Desafio Indicium

## Visão Geral

Este projeto foi desenvolvido como parte do desafio para Cientista de Dados da Indicium. O objetivo é realizar uma análise exploratória de dados (EDA) e desenvolver um modelo preditivo para estimar o preço de aluguéis temporários na cidade de Nova York, com base em um conjunto de dados fornecido. Além disso, o projeto responde a questões de negócio e propõe insights estratégicos para a precificação de imóveis na plataforma.

## Uso

Para rodar a análise exploratória e o modelo preditivo, utilize o Jupyter Notebook:
Efetue o download do arquivo .csv que contem a base de dados.

Abra o notebook modelagem e execute as células conforme.
Abra o notebook analise_exploratória_EDA e execute as células.

## Análise Exploratória de Dados (EDA)

A análise exploratória tem como objetivo entender melhor a estrutura dos dados e identificar padrões relevantes para a modelagem preditiva. Foram abordadas as seguintes questões:

- Relação entre o preço e diferentes variáveis (tipo de acomodação, localização, disponibilidade, etc.).
- Influência do número mínimo de noites e disponibilidade na precificação.
- Identificação de padrões no nome dos anúncios.
- Sugestão de locais mais indicados para investimento em aluguéis temporários.

Os insights e visualizações gerados estão documentados no notebook.

## Modelagem Preditiva

A modelagem preditiva foi realizada utilizando algoritmos de Machine Learning para prever o preço dos aluguéis. O pipeline incluiu:

1. **Pré-processamento dos dados:** Tratamento de valores ausentes, codificação de variáveis categóricas e normalização.
2. **Seleção de variáveis:** Identificação das variáveis mais relevantes para o modelo.
3. **Treinamento e avaliação:** Teste de diferentes modelos de regressão, escolha da métrica de avaliação e ajuste dos hiperparâmetros.
4. **Exportação do modelo:** O modelo final foi salvo no formato `.pkl` para futuras previsões.

## Arquivos Disponíveis

- `analise_exploratória_EDA.ipynb` - Análise exploratória dos dados.
- `modelagem.ipynb` - Modelagem preditiva.
- `modelo.pkl` - Modelo treinado salvo.
- `requirements.txt` - Lista de dependências do projeto.


## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook





