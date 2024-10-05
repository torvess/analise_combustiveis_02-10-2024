# Análise de Dados de Combustíveis no Brasil

Este projeto tem como objetivo realizar uma análise exploratória e visualização de dados sobre combustíveis no Brasil, utilizando dados públicos fornecidos pelo governo. O projeto inclui coleta, processamento e visualização de mais de 5 milhões de registros relacionados ao mercado de combustíveis.

## Descrição do Projeto

Neste repositório, você encontrará o código para a coleta de dados, processamento e análise, além de dashboards desenvolvidos no Power BI para acompanhar tendências e comportamento do mercado de combustíveis ao longo do tempo. Também foram aplicadas técnicas de visualização de dados para fornecer insights sobre preços, volume e consumo de combustíveis.

### Principais Funcionalidades

- Coleta de dados públicos de combustíveis via arquivos CSV.
- Importação de dados para um banco de dados relacional utilizando `pyodbc`.
- Análise exploratória dos dados com Python (`pandas`, `numpy`, `matplotlib`, `seaborn`).
- Geração de relatórios em PDF com os principais insights encontrados.
- Desenvolvimento de dashboards interativos no Power BI para acompanhamento em tempo real.

## Estrutura do Projeto

- **data/**: Contém os arquivos CSV originais.
- **notebooks/**: Notebooks Jupyter usados na análise exploratória.
- **scripts/**: Scripts Python para processamento e carga de dados.
- **dashboard/**: Contém o arquivo do projeto do Power BI (.pbix).
- **reports/**: PDFs gerados com as análises realizadas.

## Tecnologias Utilizadas

- **Python**: Processamento e análise de dados.
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `pyodbc`
- **SQL**: Banco de dados relacional para armazenar e manipular dados.
- **Power BI**: Desenvolvimento de dashboards interativos.
- **Jupyter Notebook**: Para a análise exploratória de dados.
- **Git**: Controle de versão.
