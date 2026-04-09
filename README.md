# Artigo:Estimativa do fator de infiltração de material particulado em ambientes residenciais

Esse estudo investiga a concentração de Material Particulado em ambientes internos. A partir de dados experimentais, pretende-se avaliar a relação entre as concentrações interna e externa de diferente poluentes, calculando o 𝐹_𝑖𝑛𝑓  e contribuições de fontes internas por meio de um modelo de balanço de massas e utilizando um modelo baseado em LOWESS () . Com base nos resultados experimentais, pretende-se desenvolver e avaliar o desempenho dos dois modelos para estimar as concentrações internas dos ambientes estudados e definir. 

**Autores:** [Seu Nome], [Co-autores]
**Revista/Conferência:** [Nome da Publicação, Ano]
**DOI:** [Link para a publicação]

## Visão Geral
Este repositório contém o código-fonte e os dados utilizados no artigo:
> *"Artigo:Análise comparativa de modelos mecanicista e estatístico para estimativa do fator de infiltração de material particulado em ambientes residenciais"*.

O objetivo deste repositório é fornecer transparência e permitir a reprodução de todas as figuras, tabelas e resultados numéricos apresentados no estudo.

## Requisitos
*   Python 3.13+
*   Bibliotecas: `pandas`, `matplotlib`, `scikit-learn` (ver `requirements.txt`)
*   Sistema operacional testado: Windows 11 (recomendado)

## Estrutura do Repositório
```text
├── README.md           <- Este arquivo
├── data/               <- Dados brutos e processados
│   ├── raw/            <- Dados brutos (originais)
│   └── processed/      <- Dados prontos para análise
├── notebooks/          <- Jupyter notebooks para análise exploratória
├── scripts/            <- Scripts Python processamento e modelagem
├── figures/            <- Figuras geradas pelo código
└── requirements.txt    <- Dependências do ambiente


** Como Reproduzir os Resultados **

Siga os passos abaixo para replicar o estudo no seu ambiente local:

1. Configuração do Ambiente

git clone
https://github.com/MelinaPeixoto/dados_artigo

cd https://github.com/MelinaPeixoto/dados_artigo
pip install -r requirements.txt

3. Execução das Análises (Reprodução)

Abra os notebooks na pasta notebooks/ para gerar os resultados.
notebooks/01-algoritmo_de_censura.ipynb
notebooks/02-modelo_mbm_notebook.ipynb
notebooks/03-modelo_lowess_notebook.ipynb


# Licença
Este projeto está licenciado sob a Creative Commons Legal Code / CC0 1.0 Universal] - veja o arquivo LICENSE para detalhes.
