## Overview

### Objective

Teach practical aspects of productionizing ML services — from training and experimenting to model deployment and monitoring.

### Target audience

Data scientists and ML engineers. Also software engineers and data engineers interested in learning about putting ML in production.

### Pre-requisites

* Python
* Docker
* Being comfortable with command line 
* Prior exposure to machine learning (at work or from other courses, e.g. from [ML Zoomcamp](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp))
* Prior programming experience (at least 1+ year)



## Syllabus

### [Module 1: Introduction](01-intro)

* What is MLOps
* MLOps maturity model
* Running example: NY Taxi trips dataset
* Why do we need MLOps
* Course overview
* Environment preparation
* Homework

[More details](01-intro)

### [Module 2: Experiment tracking and model management](02-experiment-tracking)

* Experiment tracking intro
* Getting started with MLflow
* Experiment tracking with MLflow
* Saving and loading models with MLflow
* Model registry
* MLflow in practice
* Homework

[More details](02-experiment-tracking)


### [Module 3: Orchestration and ML Pipelines](03-orchestration)

* Workflow orchestration
* Prefect 2.0
* Turning a notebook into a pipeline
* Deployment of Prefect flow
* Homework

[More details](03-orchestration)


### [Module 4: Model Deployment](04-deployment)

* Three ways of model deployment: Online (web and streaming) and offline (batch)
* Web service: model deployment with Flask
* Streaming: consuming events with AWS Kinesis and Lambda
* Batch: scoring data offline
* Homework

[More details](04-deployment)


### [Module 5: Model Monitoring](05-monitoring)

* Monitoring ML-based services
* Monitoring web services with Prometheus, Evidently, and Grafana
* Monitoring batch jobs with Prefect, MongoDB, and Evidently

[More details](05-monitoring)


### [Module 6: Best Practices](06-best-practices)

* Testing: unit, integration
* Python: linting and formatting
* Pre-commit hooks and makefiles
* CI/CD (Github Actions)
* Infrastructure as code (Terraform)
* Homework

[More details](06-best-practices)


### [Project](07-project/)

* End-to-end project with all the things above

[More details](07-project/)

