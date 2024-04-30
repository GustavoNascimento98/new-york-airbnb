[![pt-br](https://img.shields.io/badge/language-pt--br-green.svg)](https://github.com/GustavoNascimento98/new-york-airbnb/blob/main/README.md)
[![en](https://img.shields.io/badge/language-en-red.svg)](https://github.com/GustavoNascimento98/new-york-airbnb/blob/main/README-en.md)

![](img/new-york-city.jpg)

# Análise das Hospedagens em Nova York

Este projeto desenvolve um relatório abrangente do Power BI analisando hospedagens na cidade de Nova York anunciadas pelo Airbnb, oferecendo insights sobre preços, bairros populares e métricas de desempenho de crescimento.

Acesse o [relatório](https://app.powerbi.com/view?r=eyJrIjoiOGZhNGM0ZDEtYzY5OC00YzA4LTkzM2MtNzRkOTFlM2FjZjQ2IiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9):

[![](img/dashboard.gif)](https://app.powerbi.com/view?r=eyJrIjoiOGZhNGM0ZDEtYzY5OC00YzA4LTkzM2MtNzRkOTFlM2FjZjQ2IiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9)  

## Visão Geral
Este projeto tem como objetivo desenvolver um relatório no Power BI sobre hospedagens na cidade de Nova York. O relatório utiliza um conjunto de dados obtido do [kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). O objetivo é fornecer insights sobre o mercado de hospedagens em NYC, incluindo tendências de preços, bairros populares e entre outros.

## Conjunto de Dados
Desde 2008, hóspedes e anfitriões têm utilizado o Airbnb para expandir as possibilidades de viagem e apresentar uma maneira mais única e personalizada de experimentar o mundo. Este conjunto de dados descreve a atividade de listagem e as métricas em NYC, NY para 2019.

Este conjunto de dados inclui todas as informações necessárias para descobrir mais sobre os anfitriões, disponibilidade geográfica, métricas necessárias para fazer previsões e tirar conclusões.

<details>
  <summary>Dataset</summary>
</br>

| Nome da Coluna      | Data Type |
| ------------------- | --------- |
| id                  | Integer   |
| name                | Text      |
| host_id             | Integer   |
| host_name           | Text      |
| neighbourhood_group | Text      |
| neighbourhood       | Text      |
| latitude            | Decimal   |
| longitude           | Decimal   |
| room_type           | Texto     |
| price               | Decimal   |
| minimum_nights      | Inteiro   |
| number_of_reviews   | Inteiro   |
| last_review         | Date      |

</details>


## Componentes do Relatório

O relatório do Power BI é composto pelas seguintes análises:

1. **Painel de Visão Geral**: Fornece uma visão geral do mercado de hospedagens domiciliares em NYC, incluindo o número total de hospedagens, distribuição de preços médios e distribuição por distrito.

2. **Análise de Preços**: Analisa as tendências de preços ao longo do tempo e compara os preços médios em diferentes bairros e distritos.

3. **Visão Geral dos Bairros**: Explora a popularidade dos bairros com base no número de hospedagens disponíveis e seus preços médios.

4. **Métricas de Desempenho**: Avalia métricas de desempenho, como avaliação média, número de listagens e taxa de resposta.


## Próximos passos

Possíveis aprimoramentos para o relatório do Power BI incluem:

1. Integração com fontes de dados em tempo real para insights atualizados.

2. Incorporação de análise preditiva para prever tendências de preços.