# ✈️ Análise de Atrasos na Aviação Civil

## 🎯 Contexto de Negócio
Fomos acionados pela diretoria de operações para identificar os principais gargalos na malha aérea. O objetivo deste projeto é processar a base de dados de voos, investigar o comportamento das companhias aéreas e responder a 5 perguntas estratégicas de negócio para guiar futuras tomadas de decisão:

1. **Quais companhias aéreas tem mais registros de atrasos?** (Análise de performance)
2. **Existe sazonalidade nos atrasos?** (Impacto dos meses do ano e alta temporada)
3. **Qual aeroporto tem maior tempo de atraso?** (Impacto da infraestrutura)
4. **Quais são as companhias mais rápidas na média?** (Eficiência de voo e rotas)
5. **Quais são as rotas mais críticas com as maiores médias de atraso?** (Mapeamento de risco Origem ➡️ Destino)

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando Jupyter Notebook e as seguintes bibliotecas:
* **Pandas & Numpy:** Manipulação, limpeza e agregação de dados.
* **Matplotlib & Seaborn:** Criação de gráficos estáticos para análise de tendências e correlações.
* **Datetime:** Tratamento de séries temporais.

## 📊 Principais Insights de Negócio
* **Sazonalidade:** Forte correlação entre alta temporada e atrasos, com picos críticos em Junho, Julho e Dezembro.
* **Efeito Cascata:** Atrasos na partida quase invariavelmente resultam em atrasos na chegada. A recuperação de tempo em rota é ineficaz.
* **Eficiência de Voo:** A Hawaiian Airlines (HA) apresentou a maior velocidade média (476.1 MPH), impulsionada por rotas de longuíssima distância que maximizam o tempo em altitude de cruzeiro.

## 📂 Estrutura do Projeto
* `notebook.ipynb`: Código fonte com toda a análise exploratória e respostas às 5 perguntas.
* `data/`: Diretório contendo os arquivos da base de dados.

---
*Desenvolvido por Murilo*