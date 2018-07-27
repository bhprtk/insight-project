# insight-project
## Project Idea
CI/CD pipeline for data-pipeline maintained in git
## Use case
The purpose is to enable data engineers to develop data pipeline in Docker containers without having to worry about continuous integration.
## Technologies
* AWS
* Kafka
* Spark
* MongoDB
* GIT
* Jenkins
## Proposed architecture
S3 —> Kafka —> Spark —> MongoDB —> Open Source API
— Git
— CI/CD using Jenkins
## Data
Real time streaming data from New York City Taxi and Limousine Commission (TLC) Trip Record Data
