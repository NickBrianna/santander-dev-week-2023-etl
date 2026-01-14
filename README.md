# Pipeline de ETL com Python: Santander Dev Week 2023

## 📋 Descrição do Desafio
Este projeto foi desenvolvido como parte de um Lab da DIO para praticar os conceitos fundamentais de Engenharia de Dados. O objetivo é criar um pipeline **ETL** (Extração, Transformação e Carregamento) utilizando Python.

## 🛠️ Etapas do Pipeline

### 1. Extração (Extract)
A extração foi realizada a partir de um arquivo CSV (`SDW2023.csv`) contendo dados básicos de clientes, como Nome e Tipo de Cartão. Esta abordagem foi adotada como alternativa para garantir a continuidade do projeto mesmo em caso de indisponibilidade da API externa.

### 2. Transformação (Transform)
Nesta fase, utilizei Python para processar os dados e simular a integração com uma IA Generativa (como o GPT-4 da OpenAI). O script gera mensagens personalizadas de marketing para cada cliente com base em seus dados individuais.

### 3. Carregamento (Load)
Os dados transformados e as novas mensagens foram salvos em um novo arquivo consolidado (`SDW2023_com_mensagens.csv`), demonstrando o ciclo completo de entrega de dados limpos e enriquecidos.

## 🚀 Tecnologias Utilizadas
- **Python**: Linguagem principal.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Google Colab**: Ambiente de desenvolvimento em nuvem.
