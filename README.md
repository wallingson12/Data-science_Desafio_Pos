# 📊 Desafio Final - Bootcamp de Ciência de Dados

Este repositório contém o notebook de entrega do desafio final do Bootcamp de Ciência de Dados.

O projeto realiza uma análise exploratória e descritiva do consumo de energia elétrica por região e tipo de consumidor no Brasil.

## 🧾 Objetivo

O objetivo é extrair **insights relevantes** a partir de uma base de dados de consumo de energia elétrica, considerando diferentes regiões e categorias de consumo (residencial, comercial, industrial e outros).

## 🔍 Principais Análises Realizadas

- **Limpeza de dados**: remoção de linhas com dados ausentes para evitar distorções.
- **Consumo total por região**:
  - Região Sudeste lidera com mais de **4,7 bilhões de kWh**.
  - Sul (~1,6 bi), Nordeste (~1,57 bi), Centro-Oeste (~661 mi) e Norte (~633 mi).
- **Número total de consumidores por região**:
  - Sudeste > Nordeste > Sul > Centro-Oeste; dados incompletos para o Norte.
- **Consumo médio por tipo de consumo**:
  - Industrial: **536.710 kWh**
  - Residencial: **380.019 kWh**
  - Comercial: **241.786 kWh**
  - Outros: **209.883 kWh**

## 📌 Ferramentas Utilizadas

- Python 3.x
- Jupyter Notebook
- Bibliotecas:
  - `pandas` para manipulação de dados
  - `matplotlib` e `seaborn` para visualização gráfica
  - `numpy` para operações numéricas

## 📊 Insights

- Regiões mais populosas e industrializadas consomem mais energia.
- A distribuição de consumidores acompanha o desenvolvimento regional.
- O consumo médio varia significativamente por setor, com a indústria sendo a mais intensiva.

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio

pip install -r requirements.txt

jupyter notebook DESAFIO_PÓS.ipynb

jupyter notebook DESAFIO_PÓS.ipynb
