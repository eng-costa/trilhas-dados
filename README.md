# Desafio 4 — Trilha de Ciência de Dados

Este repositório faz parte da **Trilha de Ciência de Dados** do programa *Trilhas - Ciência de Dados*. O objetivo deste desafio é realizar uma análise exploratória completa de um conjunto de dados fornecido, aplicando técnicas de pré-processamento, visualização e estatística descritiva com ferramentas como `Pandas`, `NumPy`, `Seaborn` e `Matplotlib`.

## 📁 Arquivos do repositório

- [`Trilhas2B-Desafio4.csv`](https://github.com/eng-costa/trilhas-dados/blob/main/Trilhas2B-Desafio4.csv) — Base de dados em CSV  
- `Trilhas2B-Desafio4.xlsx` — Base de dados em Excel  
- `analise_exploratoria.ipynb` — Código da análise em Jupyter Notebook  
- `relatorio_final.pdf` — Relatório final da análise

## 📌 Etapas realizadas

1. **Carregamento e renomeação de colunas**
   - Renomeadas para letras minúsculas com `pandas`.

2. **Tratamento de dados**
   - Preenchimento de valores ausentes (NaN)
     - Numéricos com mediana.
     - Categóricos com moda.
   - Correção de inconsistências em colunas categóricas.
   - Remoção de duplicatas.
   - Detecção e substituição de outliers.

3. **Exploração de dados**
   - Agrupamentos com `groupby()` para colunas categóricas (`estado`, `genero`).
   - Visualizações com gráficos `barplot`, `boxplot`, `histplot`, etc.
   - Análises descritivas com `describe()`.

4. **Estatísticas específicas**
   - Média e mediana do saldo na conta para clientes:
     - Abaixo e acima de 40 anos.
     - Que saíram ou permaneceram.
   - Perfil predominante dos clientes que saíram (idade, estado, gênero, saldo, bens).

## 💻 Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (Google Colab)

## 📊 Resultados

O projeto fornece uma visão clara sobre os dados dos clientes de uma instituição financeira, revelando padrões de comportamento, perfis de saída, distribuição de patrimônio e saldo, além de reforçar a importância do tratamento de dados faltantes e outliers em um pipeline de dados real.

---

🧑‍💻 Desenvolvido por [Lucas Costa](https://github.com/eng-costa)  
🚀 Projeto integrante da **Trilha de Ciência de Dados**
