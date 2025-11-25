# Food Delivery - Análise de Dados

## Visão Geral
Este projeto realiza uma análise completa de entregas de delivery, utilizando Python (Pandas) para limpeza e criação de métricas, e Power BI para visualização e geração de insights. O objetivo é identificar padrões de desempenho, entender os principais fatores que influenciam atrasos e sugerir melhorias operacionais.

## Objetivos do Projeto
O projeto foi desenvolvido com foco principal em identificar os motivos dos atrasos nas entregas. Para isso, foram criadas métricas e classificações que permitiram quantificar o nível de dificuldade de cada entrega, considerando múltiplos fatores operacionais. Os objetivos foram:

- Identificar os principais fatores que influenciam atrasos.

- Criar pontuações de dificuldade para:

    * Condições climáticas no momento da entrega.

    * Distância percorrida.

    * Nível de tráfego.

- Analisar o impacto do nível de experiência do entregador.

- Avaliar diferenças de desempenho entre diferentes meios de transporte.

- Consolidar todos os achados em um dashboard claro e orientado a tomada de decisão.

## Tecnologias Usadas

- **Python 3.x** (bibliotecas: pandas, numpy)  
- **Power BI Desktop** (visualizações interativas, gráficos de barras, cartões, etc.)  
- **Google Colab** (para notebooks interativos e reprodutíveis)  
- **Git/GitHub** (versionamento e portfólio online)  


## Estrutura do Repositório

A organização do projeto foi estruturada para facilitar manutenção, reprodutibilidade e clareza. A pasta contém:

* data/

     * raw/ – Contém os dados originais: Food_Delivery_Times.csv

     * processed/ – Contém os dados tratados e prontos para análise: df_food_delivery.csv

* notebooks/

     * Contém notebooks do projeto, incluindo tratamento e análise dos dados: 01_tratamento_dados_food_delivery.ipynb

* dashboard/

     * Contém o dashboard do Power BI criado para visualização dos dados: dashboard_food_delivery.pbix

* images/

     * Contém prints do dashboard e outras imagens relevantes para documentação do projeto



## Estrutura da Base de Dados

O dataset utilizado contém as seguintes colunas principais:

- Order_ID – Identificação única da entrega

- Distance_km – Distância percorrida

- Distance_Level_Score – Pontuação do nível de dificuldade pela distância

- Weather – Condição climática

- Weather_Level_Score – Pontuação do nível de dificuldade pelo clima

- Traffic_Level – Nível de tráfego

- Traffic_Level_Score – Pontuação do nível de dificuldade pelo tráfego

- Time_of_Day – Período do dia (Morning, Afternoon, Evening, Night)

- Vehicle_Type – Meio de transporte utilizado

- Preparation_Time_min – Tempo de preparo do pedido

- Courier_Experience_yrs – Experiência em anos do entregador

- Courier_Experience – Categoria de experiência (Iniciante, Intermediário, Sênior)

- Delivery_Time_min – Tempo de entrega estimado

- Delivery_Time_Total_min – Tempo total de entrega (incluindo preparo e deslocamento)

- Delivery_Time_Category – Categoria de entrega (Rápida, Normal, Atrasada)

- Speed_Mean_kmh – Velocidade média em km/h

- Minutes_per_km – Minutos por km

- Route_Minutes_per_km – Tempo de rota por km (considerando métricas de dificuldade)

- Total_Level_Score – Pontuação total de dificuldade da entrega

## Contato

- **Autor:** Mitsuyoshi Nakamura
- **Email:** mitsuyoshijunior@gmail.com 
- **LinkedIn:** [linkedin.com/mitsuyoshijunior](https://www.linkedin.com/in/mitsuyoshijunior)  
