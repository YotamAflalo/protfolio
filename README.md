# Data Scientist

#### Technical Skills: Python, SQL, AWS, Cypher, NEO4J, R, MLOPS, Docker

## Education
- M.S., economics	| The Hebrew University of Jerusalem (_May 2023_)
  grade: 97, Dean's list 2023,graduation with first class honors award of excellence for the thesis work. 			        		
- B.S., law and economics | The Hebrew University of Jerusalem (_May 2019_)
  dean's lists in the years 2016, 2017, 2018.
- pass lawyers bar exam (_2020_)
- Practical Data Science - 260 hours | Naya College (_2023_)
- MLOPS  - 170 hours | Naya College (_2024_)
#### Non-academic training between 2023-2024:
- **IDF** - Cloud Economic management (Nimbus, AWS, GCP and Azure)
- **Neo4j** graph-academy* - Neo4j Certified Professional
- **udmy** - MySQL Bootcamp
- **Coursera** - Deep Learning Specialization by DeepLearning.AI ( 5 courses)

## Work Experience
**Legal Advisor and innovation officer (captain's rank) (_April 2019 - December 2024_)**
- took part in Developing and implementing technological tools for the legal department within the Azure environment, including  a Retrieval Augmented Generation (RAG) model for addressing legal queries, a summary model and automatic document labeling system. The project received an award of excellence from the chief military attorney general Yifat Tomer Yerushalmi.
- Legal Advisor specializing in energy, communications, water, quarry, and construction law.
- Managed teams, provided legal counsel to senior executives, and represented the organization in Knesset hearings.
- Board Member of the Quarry Restoration Fund for the Judea and Samaria region from 2022 to 2024.

**Research Assistant and Teaching Assistant at  The Hebrew University of Jerusalem (_Jan 2017 - Jan 2019_)**
- Research assistant for a collaborative project with Brown University, estimating the empirical impact of changing protective tariffs in Israel on employment
- teaching assistant.

## Projects
### 1. Healthcare Chatbot with LLM-Langchain-Agent and Graph-RAG Architecture

[project repo](https://github.com/YotamAflalo/chyper-graphRAG-with-langchain-and-neo4j)

This project implements a chatbot utilizing a Graph-RAG architecture, built with Python and Neo4j. I created a knowledge graph from thousands of healthcare-related pages using state-of-the-art LLMs. The chatbot operates through a Langchain agent that leverages this knowledge graph as its knowledge base for answering questions. The agent employs text-to-Cypher techniques to query the knowledge graph and generate responses to user queries.

![Knowlage-graph-example](/assets/img/knowlage_graph_example.png)

### 2. MLOps-TeleChurnPredictor

[project repo](https://github.com/YotamAflalo/MLOps-TeleChurnPredictor)

This project implements a full MLOPS solution for machine learning model for customer churn prediction, utilizing FastAPI and Apache Beam. It includes a comprehensive MLOps pipeline with monitoring, batch processing, and CI/CD integration.
The project include this features:
- FastAPI application for single predictions
- Apache Beam implementation for batch processing
- Monitoring of API and machine with Prometheus
- Error monitoring and alerting with Grafana and Grafana Standing Dashboard
- Automated scheduler for batch processing
- PostgreSQL database for prediction and data storage
- Whylogs data drift monitoring
- Full CI/CD pipeline and testing

The presenation of this project can be found [here](https://gamma.app/docs/Customer-Churn-Prediction-MLOps-System-klmmvju41ctqpmv) 
System Architecture Diagram;
![dashboard](/assets/img/mlops_architecture.png)
System dashboard:
![dashboard](/assets/img/dashboard.png)

### 3. Book Recommendation System with Hybrid Approach


[project repo](https://github.com/YotamAflalo/projects/tree/main/book%20recommendation%20system)

A personalized book recommendation system combining Matrix Factorization, One-Class SVM, and deep learning. Built using TensorFlow, the system analyzes:
- User reading history and preferences
- Book descriptions and cover images
- Author-based user reviews
The neural network implementation replicates Matrix Factorization while incorporating multiple data signals for accurate, personalized book recommendations based on users' reading history.
![books](/assets/img/books.png)


### 4. Terraform with AWS Web server

[project repo](https://github.com/YotamAflalo/terraform-AWS-Web-Server-Project/tree/main)

This project uses Terraform to provision a basic web server infrastructure on AWS. It sets up a VPC, subnet, internet gateway, route table, security group, and an EC2 instance running Apache2.

see more at [my GitHub page](https://github.com/YotamAflalo)

### 5. RAG Chatbot Evaluation System
[project repo](https://github.com/YotamAflalo/RAG-Chatbot-Evaluation-System/tree/main)

Built an evaluation script for RAG-based chatbots that assesses:
- Answer accuracy
- Question-answer relevance
- Hallucination detection
- Context chunk selection quality
The system provides quantitative metrics to measure RAG performance and identify areas for optimization.
## Publications

1. Re-examining the relationship between labor market concentration and monopsony power, using the minimum wage as a case study, Aflalo Yotam, 2023 [the peper](https://github.com/YotamAflalo/projects/blob/main/Re-examining%20the%20relationship%20between%20labor%20market%20concentration%20and%20monopsony%20power%2C%20using%20the%20minimum%20wage%20as%20a%20case%20study/Finel%20paper%20%20-%20Yotam%20Aflalo%20thesis%20-%20Re-examining%20the%20relationship%20between%20labor%20market%20concentration%20and%20monopsony%20power%2C%20using%20the%20minimum%20wage%20as%20a%20case%20study.pdf)
2.  אישור בשתיקה: מנגנון ברירת מחדל לצמצום עלויות הרגולציה, גיא מור ויותם אפללו, 2018 [the peper](https://drive.google.com/file/d/1JlepLzYYLhMBoA8ysD6Gk-g-Jz3WuXXR/view)
