# Cybersecurity Threats Analysis (2015–2024)

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Analysis-orange.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-green.svg)](https://seaborn.pydata.org/)

## 📌 Descrição

Este projeto realiza uma **análise exploratória de dados (EDA)** do dataset [Global Cybersecurity Threats (2015–2024)](https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024), que reúne incidentes globais de segurança cibernética ocorridos ao longo da última década.

O objetivo é **identificar padrões, tendências e setores mais visados**, auxiliando pesquisas e decisões estratégicas na área de cibersegurança.

---

## 📊 Fonte dos Dados

- **Origem**: Kaggle (Atharva Soundankar)
- **Período coberto**: 2015 a 2024
- **Registros**: ~3.000 incidentes
- **Principais colunas**:
  - `Country`
  - `Year`
  - `Attack Type`
  - `Target Industry`
  - `Financial Loss (in millions USD)`
  - `Users Affected`
  - `Source of Attack`
  - `Vulnerability Type`
  - `Defense Mechanism`
  - `Resolution Time (hours)`

---

## 🔍 Objetivos da Análise

1. **Explorar e limpar os dados**
2. **Identificar ataques mais comuns** e sua evolução temporal
3. **Mapear setores mais afetados**
4. **Analisar perdas financeiras e impacto em usuários**
5. **Visualizar padrões geográficos e temporais**

---

## 📈 Principais Insights (Exemplos)

- **Ataques de Phishing** e **DDoS** estão entre os mais frequentes.
- Setores de **Tecnologia** e **Bancos** aparecem como os mais visados.
- Picos de incidentes coincidem com eventos globais relevantes (ex.: pandemia de 2020).
- Perdas financeiras variam amplamente, com alguns casos ultrapassando **US$ 500 milhões**.

*(Adicione aqui imagens geradas no notebook, por exemplo:)*

![Ataques por Ano](./images/ataques_por_ano.png)
![Setores Mais Visados](./images/setores_visados.png)

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.9+**
- [Pandas](https://pandas.pydata.org/) – Manipulação e análise de dados
- [Matplotlib](https://matplotlib.org/) – Visualizações gráficas
- [Seaborn](https://seaborn.pydata.org/) – Gráficos estatísticos

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/30Lima/Cybersecurity-Analysis.git
