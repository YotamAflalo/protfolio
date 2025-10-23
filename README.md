# Data Scientist and AI softwere engineer

#### Technical Skills: Python, SQL, AWS, Cypher, NEO4J, R, MLOPS, Docker

## Education
- M.S., economics	| The Hebrew University of Jerusalem (_May 2023_)
  grade: 97, Dean's list 2023, graduation with first class honors, and an award of excellence for my thesis work. 			        		
- B.S., law and economics | The Hebrew University of Jerusalem (_May 2019_),
  Dean's lists in the years 2016, 2017, 2018
- Passed lawyers bar exam (_2020_)
- Practical Data Science - 260 hours, Naya College (_2023_)
- MLOPS  - 235 hours, Naya College (_2024_)

#### Non-academic training:
- **IDF** - Cloud Economic management (Nimbus, AWS, GCP and Azure)
- **AWS** - AWS Certified Cloud Practitioner 
- **AWS** - AWS Certified AI Practitioner 
- **Neo4j graph-academy** - Neo4j Certified Professional
- **Udmy** - MySQL Bootcamp
- **Coursera** - Deep Learning Specialization by DeepLearning.AI ( 5 courses)

## Work Experience
**Migdal - lead software engineer (ai spesialist) (_March 2025 - present_)**
- research and development of AI-based systems and agentic solutions for the insurance company Migdal
- Implementing projects from start to finish in AWS's Kubernetes (EKS) environment, developing systems in Python with Bedrock FM, Bedrock agents, OpenSearch, KMS, S3, and other peripheral tools.
- Integrating into other developers' projects and establishing evaluation and prompt engineering mechanisms
- Developing an internal OCR solution and implementing it as a component of the information accessibility project for insurance agents

**Legal Advisor and innovation officer at the IDF (released at the rank of Captain) (_April 2019 - December 2024_)**
- Took part in developing and implementing technological tools for the legal department within the Azure environment, including  a Retrieval Augmented Generation (RAG) model for addressing legal queries, a summary model and automatic document labeling system. The project received an award of excellence from the chief military attorney general Yifat Tomer Yerushalmi.
- Legal Advisor specializing in energy, communications, water, quarry, and construction law.
- Managed teams, provided legal counsel to senior executives, and represented the organization in Knesset (Parliament) hearings.
- Board Member of the Quarry Restoration Fund for the Judea and Samaria region from 2022 to 2024.

**Research Assistant and Teaching Assistant at  The Hebrew University of Jerusalem (_Jan 2017 - Jan 2019_)**
- Research assistant for a collaborative project with Brown University, estimating the empirical impact of changing protective tariffs in Israel on employment.
- Teaching assistant.

## Projects
### 1. Healthcare Chatbot with LLM-Langchain-Agent and Graph-RAG Architecture

[Project repo](https://github.com/YotamAflalo/chyper-graphRAG-with-langchain-and-neo4j)

This project implements a chatbot utilizing a Graph-RAG architecture, built with Python and Neo4j. I created a knowledge graph from thousands of healthcare-related pages using state-of-the-art LLMs. The chatbot operates through a Langchain-agent that leverages this knowledge graph as its knowledge base for answering questions. The agent uses Text-to-Cypher techniques to query the knowledge graph and generate responses to users queries.

![Knowlage-graph-example](/assets/img/knowlage_graph_example.png)

### 2. MLOps-TeleChurnPredictor

[Project repo](https://github.com/YotamAflalo/MLOps-TeleChurnPredictor)

This project implements a full MLOPS solution for machine learning model for customer churn prediction, utilizing FastAPI and Apache Beam. It includes a comprehensive MLOPS pipeline with monitoring, batch processing, and CI/CD integration.

The project include these features:
- FastAPI application for single predictions;
- Apache Beam implementation for batch processing;
- Monitoring of API and machine with Prometheus;
- Error monitoring and alerting with Grafana and Grafana Dashboard;
- Automated scheduler for batch processing;
- PostgreSQL database for prediction and data storage;
- data drift monitoring;
- Full CI/CD pipeline and testing.

[The presenation of this projecthere](https://gamma.app/docs/Customer-Churn-Prediction-MLOps-System-klmmvju41ctqpmv)

System Architecture Diagram:
![dashboard](/assets/img/mlops_architecture.png)
System dashboard:
![dashboard](/assets/img/dashboard.png)

### 3. Book Recommendation System with Hybrid Approach


[Project repo](https://github.com/YotamAflalo/projects/tree/main/book%20recommendation%20system)

A personalized book recommendation system combining Matrix Factorization, One-Class SVM, and deep learning. Built using TensorFlow. the system analyzes:
- User reading history and preferences;
- Book descriptions and cover images;
- Author-based user reviews.

The neural network implementation replicates Matrix Factorization while incorporating multiple data signals for accurate, personalized book recommendations based on users' reading history.
![books](/assets/img/books.png)


### 4. Terraform with AWS Web server

[Project repo](https://github.com/YotamAflalo/terraform-AWS-Web-Server-Project/tree/main)

This project uses Terraform to provision a basic web server infrastructure on AWS. It sets up a VPC, subnet, internet gateway, route table, security group, and an EC2 instance running Apache2.


### 5. RAG Chatbot Evaluation System
[Project repo](https://github.com/YotamAflalo/RAG-Chatbot-Evaluation-System/tree/main)

This projects includes an evaluation script for RAG-based chatbots which assesses:
- Answer accuracy;
- Question-answer relevance;
- Hallucination detection;
- Context chunk selection quality.

The system provides quantitative metrics to measure RAG performance and identify areas for optimization.

see more at [my GitHub page](https://github.com/YotamAflalo)


## Publications

1. Re-examining the relationship between labor market concentration and monopsony power, using the minimum wage as a case study, Aflalo Yotam, 2023 [the peper](https://github.com/YotamAflalo/projects/blob/main/Re-examining%20the%20relationship%20between%20labor%20market%20concentration%20and%20monopsony%20power%2C%20using%20the%20minimum%20wage%20as%20a%20case%20study/Finel%20paper%20%20-%20Yotam%20Aflalo%20thesis%20-%20Re-examining%20the%20relationship%20between%20labor%20market%20concentration%20and%20monopsony%20power%2C%20using%20the%20minimum%20wage%20as%20a%20case%20study.pdf)
2.  אישור בשתיקה: מנגנון ברירת מחדל לצמצום עלויות הרגולציה, גיא מור ויותם אפללו, 2018 [the peper](https://drive.google.com/file/d/1JlepLzYYLhMBoA8ysD6Gk-g-Jz3WuXXR/view)
