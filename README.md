# 🧪 Teste de Aprendizado: Pipeline ETL com PySpark no Databricks

Este notebook (`Teste Pipeline ETL de API pública IBGE.ipynb`) é um experimento prático desenvolvido para estudar e validar conceitos de construção de pipelines ETL (Extract, Transform, Load) utilizando PySpark dentro do ambiente Databricks.

## 📌 Objetivo

Demonstrar o funcionamento de um pipeline ETL básico com as seguintes etapas:

- **Extração** de dados de uma API pública do IBGE, relativamente simples e básica.
- **Transformação** dos dados com operações PySpark (limpeza, padronização e agregações)
- **Carga** dos dados transformados em delta table no volume do catalogo.

## ⚙️ Tecnologias Utilizadas

- [Databricks](https://www.databricks.com/)
- [Apache Spark (PySpark)](https://spark.apache.org/docs/latest/api/python/)
- Python 3.x
- Notebooks `.ipynb`

## 📁 Estrutura do Notebook

1. **Configuração do ambiente**
   - Inicialização da sessão Spark
   - Definição de parâmetros e caminhos

2. **Extração**
   - Leitura de dados simulados
   - Visualização inicial

3. **Transformação**
   - Limpeza de dados
   - Enriquecimento e agregações

4. **Carga**
   - Escrita dos dados transformados

## 📚 Aprendizados

- Como estruturar um pipeline ETL modular com PySpark
- Boas práticas de manipulação de dados em Spark
- Integração com o ambiente Databricks para testes e visualizações
