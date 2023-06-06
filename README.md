# Covid19 Data Pipeline
Develop an end-to-end Data Pipeline for European Covid19 data related to cases and deaths, hospital admissions and testing on Azure Data Factory to use for reporting and analysis purposes.

## Architecture Diagram

![ArchitectureDiagram](https://github.com/atikahhrn/covid19-project/assets/108443483/ceb989cc-173e-490d-ba4b-1cf5fd81b837)

- Build a data lake in Azure by integrating the data related to COVID-19 from the European Center for Disease Prevention and Control (ECDC) website and also some data related to the European population from Eurostat.
- Transform this data using data flows within Azure Data Factory as well as external compute resources such as Databricks.
- Transformed data will be ingested into Data Lake ready for predictions using machine learning models.
- The necessary data required for reporting the trends are loaded into the SQL database.
- Integrate and orchestrate all of these data pipelines using Azure Data Factory.
- Create some dashboards in Power BI to see the trends about the COVID-19 outbreak in Europe.

## Services Used
- Azure Data Factory (Dataflows, Linked Services, Triggers)
- Azure Databricks
- Azure Blob Storage
- Azure Lake Storage Gen2
- Azure Key-Vault
- Azure SQL Database

## Results
![Covid-19 Trends By Country-1](https://github.com/atikahhrn/covid19-project/assets/108443483/102bf50f-79f6-4d87-aabf-2b213c32016d)
![Covid-19 Trends By Country-2](https://github.com/atikahhrn/covid19-project/assets/108443483/d79017fe-2ae6-494e-b196-4ac95d8fd3f3)
![Covid-19 Trends By Country-3](https://github.com/atikahhrn/covid19-project/assets/108443483/74bfb435-1ba5-4911-8ea6-815ee8035107)
