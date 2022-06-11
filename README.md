## springboot_liquibase_oracle
This is a Maven project that demos how to run a Spring application in CI/CD with the Liquibase spring integration and Liquibase extension.
1. The workflow will first run (https://www.liquibase.com/quality-checks)[Quality Checks] using the Liquibase Maven Plugin
2. If the Quality Checks run successfully, the workflow will then build the application.  That will include running the database changes with Liquibase Spring integration and packaging the application code (compiling, running unit tests and generating artifacts).
