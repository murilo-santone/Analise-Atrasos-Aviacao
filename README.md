# ✈️ Análise de Atrasos na Aviação Civil

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** para identificar padrões, tendências e fatores críticos que influenciam atrasos em voos comerciais. O objetivo é responder perguntas de negócio através de dados quantitativos e visuais.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando Jupyter Notebook e as seguintes bibliotecas para processamento e visualização:
* **Pandas & Numpy:** Manipulação e limpeza de dados.
* **Matplotlib & Seaborn:** Criação de gráficos estáticos para análise de tendências e correlações.
* **Datetime:** Tratamento de séries temporais.

## 📊 Principais Insights de Negócio

### 1. Ranking de Atrasos por Companhia
Classificamos as empresas em grupos de performance baseados no tempo médio de atraso.
* **Maior Índice de Atrasos:** F9 (Frontier Airlines), EV (ExpressJet), YV (Mesa Airlines).
* **Melhor Performance (Menores Atrasos):** HA (Hawaiian), AS (Alaska Airlines), AA (American Airlines).

> **Nota:** As empresas foram analisadas tanto na partida quanto na chegada, mantendo consistência no ranking de performance.

### 2. Sazonalidade e Tendências Temporais
Identificou-se uma forte correlação entre períodos de alta temporada e o aumento nos atrasos:
* **Picos de Atraso:** Junho, Julho e Dezembro.
* **Causa Provável:** Aumento do fluxo de passageiros (férias) e maior demanda operacional não suportada pela infraestrutura atual.

### 3. Correlação Partida vs. Chegada
A análise confirmou uma **correlação positiva forte**:
* Atrasos na partida quase invariavelmente resultam em atrasos na chegada. A recuperação de tempo durante o voo (rota) mostrou-se ineficaz para mitigar atrasos iniciais significativos.

---

## 📂 Estrutura do Projeto
* `notebook.ipynb`: Código fonte com toda a análise exploratória, tratamento de dados e geração dos gráficos.
* `datasets/`: Arquivos csv utilizados (se aplicável).

## 📢 Conclusão
A análise sugere que medidas operacionais para mitigar atrasos devem ser focadas na **etapa de partida (solo)** e no reforço de infraestrutura durante os meses de **Junho, Julho e Dezembro**, onde o sistema aéreo opera acima da capacidade ideal.

---
*Desenvolvido por Murilo Santone*
