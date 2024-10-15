# COVID-19 Brasil Dashboard

> Este projeto apresenta uma análise exploratória dos dados de casos e vacinação da COVID-19 no Brasil. Utilizando dados da **Universidade Johns Hopkins** e da **Universidade de Oxford**, o objetivo é proporcionar insights sobre a evolução da pandemia e a cobertura vacinal no Brasil em 2021, além de disponibilizar um **dashboard interativo** para visualização de métricas relevantes.

# Sobre o Projeto

>  O projeto utiliza **Python** e bibliotecas como **Pandas** e NumPy para processar os dados, calcular tendências de casos, médias móveis, taxas de variação e tendências (estabilidade, crescimento ou queda) ao longo do tempo. Além disso, esses dados são transformados em visualizações e gráficos interativos no **Google Data Studio**.

# Funcionalidades do Projeto:

*   **Casos confirmados e óbitos:** Visualização dos casos e mortes diárias, além das médias móveis de 7 dias.
*   **Tendências de casos e mortes:** Indicadores de variação de 14 dias para mostrar se os números estão subindo, estáveis ou caindo.
*   **Vacinação:** Percentuais da população vacinada (1ª, 2ª e 3ª doses).
*   **Mapa interativo:** Permite selecionar estados brasileiros e obter detalhes sobre os dados regionais.
*   **Filtros dinâmicos:** Os usuários podem filtrar os dados por estado e por datas para realizar análises personalizadas.
  
# Tecnologias Utilizadas

* **Python:** Para processamento e análise de dados.
* **Pandas:** Manipulação de DataFrames e cálculos das médias móveis e tendências.
* **NumPy:** Operações matemáticas e cálculo de variações.
* **Google Data Studio:** Criação de dashboard interativo para visualização dos dados de forma intuitiva.

# Como Executar o Projeto

1.   Clone o repositório:
    
     **git clone https://github.com/seu-usuario/covid-dashboard.git**
     
2.   Instale as dependências necessárias:
   
     **pip install -r requirements.txt**
   
3.   Execute o script principal para realizar a análise de dados:
   
     **python main.py**

4.   Acesse o dashboard interativo para visualizar as métricas e gráficos:
   
     https://lookerstudio.google.com/u/2/reporting/94f4db85-55cd-486e-89ca-ba417eaff0c0/page/wYXFE
     
#    EStrutura do Projeto

├── data                # Arquivos de dados (casos e vacinação)

├── notebooks           # Notebooks Jupyter utilizados para análise exploratória

├── scripts             # Scripts Python para processamento dos dados

├── dashboard           # Link para o dashboard no Google Data Studio

├── README.md           # Descrição do projeto

└── requirements.txt    # Dependências do projeto

# Dashboard Interativo

O projeto também conta com um **dashboard interativo**, onde é possível visualizar os dados de COVID-19 no Brasil em tempo real. O usuário pode explorar dados de diferentes estados, casos confirmados, óbitos e a evolução da vacinação de maneira visual.



