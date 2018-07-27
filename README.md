# insight-project
## Project Idea (1-sentence)
CI/CD pipeline for data-pipeline written in Docker containers
## What is the purpose, and most common use cases?
The purpose is to enable data engineers to develop data pipeline in Docker containers without having to worry about continuous integration.
## Which technologies are well-suited to solve those challenges? (list all relevant)
* Docker
* Kubernetes
* Jenkins
## Proposed architecture
S3 —> Kafka —> Spark —> MongoDB —> Open Source API
— Git
— CI/CD using Jenkins
## Data: Talk in Numbers (size, volume, complexity)
Real time streaming data from New York City Taxi and Limousine Commission (TLC) Trip Record Data
