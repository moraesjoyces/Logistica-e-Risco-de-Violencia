
# Logistica-e-Risco-de-Violencia

O código realiza uma análise completa dos dados de entregas no Distrito Federal, desde a coleta e limpeza até a visualização e análise. Ele fornece uma visão geral das entregas em relação ao nível de violência em diferentes áreas.

## Pré-requisitos

Antes de executar o código, certifique-se de ter as seguintes bibliotecas instaladas:

- `datetime`
- `json`
- `os`
- `re`
- `requests`
- `geopy`
- `numpy`
- `pandas`
- `seaborn`
- `beautifulsoup`
- `unidecode`

## Como executar o projeto

1. Faça o download dos arquivos `deliveries.json`, 'deliveries-geodata.csv' e indicadoressegurancapublicamunic.xlsx e certifique-se de que ele esteja localizado no mesmo diretório que o script Python.

2. Execute o script Python em um ambiente de desenvolvimento compatível, como Jupyter Notebook, Spyder ou qualquer outro editor de sua preferência.

3. O código fará Wrangling da estrutura em um DataFrame Pandas, serão realizadas várias operações de limpeza e transformação, incluindo a normalização de dados aninhados. Em seguida será feita a Exploração do schema e verificação de valores ausentes no DataFrame.
Para realizar a Manipulação de Dados serão realizadas operações de Enriquecimento de dados, Geocodificação, Agregação e fusão de dados e Cálculo de novas variáveis. Para finalizar serão ão criadas visualizações de dados para analisar a relação entre as entregas e o nível de violência em diferentes áreas do Distrito Federal, incluindo
Plotagem de entregas em um mapa usando Geopandas. Criação de gráficos de barras para visualizar o número de entregas em diferentes níveis de violência. 


## Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT).
