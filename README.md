//******************************PORTUGUÊS******************************//

# FactoryStockETL-ISI-IPCA

Projeto de Integração de Sistemas de Informação que implementa um processo ETL em KNIME para a gestão de stock e produção fabril. O workflow integra dados de ficheiros CSV/Excel, aplica regras de negócio e validações, carrega a informação numa base de dados SQLite e envia os resultados para dashboards em Power BI, incluindo também o envio de alertas por email.

## Funcionalidades principais

* Extração de dados de produção, stock e desperdício a partir de ficheiros CSV/Excel.

* Transformação de dados em KNIME:
  * Limpeza e normalização de campos.
  * Aplicação de regras de negócio (classificação de stock, estados, etc.).
  * Junção de múltiplas fontes de dados (ex.: stock, produtos, lotes).

* Carga dos dados em base de dados SQLite através de nós DB Writer, DB Update e DB SQL Executor.

* Integração com Power BI:
  * Autenticação via Microsoft Authenticator.
  * Envio de dados consolidados para um dataset em Power BI.
  * Suporte à criação de dashboards de stock e produção.

* Envio de alertas por email (ex.: stock crítico ou situações anómalas).

* Estrutura de workflow modular em KNIME, organizada em blocos de extração, transformação, carga e integração.

//******************************ENGLISH******************************//

# FactoryStockETL-ISI-IPCA

Information Systems Integration project implementing an ETL process in KNIME for factory stock and production management. The workflow integrates data from CSV/Excel files, applies business rules and validations, loads the information into a SQLite database and sends the results to Power BI dashboards, also supporting automatic email alerts.

## Main Features

* Extraction of production, stock and waste data from CSV/Excel files.

* Data transformation in KNIME:
  * Data cleaning and field normalization.
  * Business rule application (stock classification, status handling, etc.).
  * Joining multiple data sources (e.g. stock, products, batches).

* Loading of data into a SQLite database using DB Writer, DB Update and DB SQL Executor nodes.

* Integration with Power BI:
  * Authentication via Microsoft Authenticator.
  * Sending consolidated data to a Power BI dataset.
  * Support for stock and production monitoring dashboards.

* Automatic email alerts (e.g. critical stock or anomalous situations).

* Modular KNIME workflow structure, organized into extraction, transformation, loading and integration blocks.
