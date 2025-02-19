# Web App de Análise de Dados de Veículos
Resultado Final: https://web-app-lecture-tripleten.onrender.com

# Descrição do Projeto

Este projeto tem como objetivo aprimorar habilidades de engenharia de software através do desenvolvimento de um aplicativo web interativo para análise exploratória de dados. O aplicativo utiliza Streamlit para criar visualizações dinâmicas a partir de um conjunto de dados de vendas de veículos.

# Funcionalidades

Carregamento de Dados: Leitura de um arquivo CSV contendo informações sobre vendas de carros.

# Visualização de Dados:

Geração de histogramas interativos usando Plotly Express.

Criação de gráficos de dispersão para análise de tendências.

# Interface Intuitiva:

Opções para visualizar os gráficos através de botões.

# Tecnologias Utilizadas

Linguagem: Python

Bibliotecas: Pandas, Streamlit, Plotly Express

Hospedagem: Deploy na nuvem utilizando Render

# Estrutura do Projeto

/
├── notebooks/            # Análise exploratória de dados
│   ├── EDA.ipynb
├── streamlit/            # Configuração para deploy no Render
│   ├── config.toml
├── app.py                # Código principal do aplicativo
├── vehicles_us.csv       # Conjunto de dados
├── requirements.txt      # Dependências
├── README.md             # Documentação

# Deploy

Para que o aplicativo funcione corretamente no Render, um arquivo de configuração foi adicionado em streamlit/config.toml. O deploy pode ser realizado conectando o repositório ao Render e configurando as variáveis adequadas.

Contribuição

Sinta-se à vontade para contribuir com melhorias no código ou novas funcionalidades!

Este projeto proporciona prática em manipulação de dados, criação de dashboards e implantação de aplicativos na nuvem.

