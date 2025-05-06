This repository includes a complete data pipeline project for BasketCraft, by combining lesson exercises and Quiz 3 to show how a data analysis workflow follows 'real life'. Orders and products for the exercises are extracted from an AWS RDS MySQL source and loaded to an AWS RDS Postgres database with Python and SQLAlchemy, while website sessions for the quiz are extracted from an AWS RDS Postgres source. Structured dbt models clean and transform the data in the staging and warehouse layers. All automation is automated through GitHub Actions and using GitHub Secrets for secure credential management. Images of the final output are shown in Looker Studio dashboards, which are for website_sessions metrics. Using Python, dbt, SQL, Github, and Looker Studio, this project emphasizes the data analyst, data engineer, and analytics engineer responsibilities.

[basket-craft-data-pipeline.pdf](https://github.com/user-attachments/files/20052815/basket-craft-data-pipeline.pdf)

Unlisted Link: https://lookerstudio.google.com/reporting/728a3d44-2d2f-41cf-ba02-003a21c72d9e

