# Overview
This project involves a real-time data streaming simulation using a variety of technologies, designed to handle and process streaming data effectively.

# Technologies Used
### Apache Kafka: 
This is the backbone for streaming data in the project. Kafka acts as a distributed messaging system, efficiently handling high-throughput data streams. It's responsible for reliably transmitting data from the source to various components in the project, ensuring low latency and fault tolerance in data processing pipelines.

### Apache Spark: 
Spark serves as the processing engine. It's used for analyzing the streaming data in real-time. Its fast, in-memory computation capabilities allow for quick data transformation, aggregation, and analysis, providing insights from the streamed data with minimal delay.

### Cassandra: 
As the project's database, Cassandra stores the processed data. Its distributed architecture ensures high availability and scalability, making it ideal for managing the large volumes of data produced and processed in real-time streaming scenarios.

### Docker & Docker Compose: 
These tools are crucial for environment management. Docker containers encapsulate the project's components, ensuring consistent environments across different development and production setups. Docker Compose orchestrates the multi-container setup, simplifying the deployment and networking of the Kafka, Spark, and Cassandra services.

### Apache Airflow: 
This tool manages the project's workflows. It schedules, orchestrates, and monitors the data pipelines, ensuring that the data streaming, processing, and storage processes are executed in the right order and at the right time.

# Usage
This project simulates a real-time data streaming environment. It fetches data from an API, streams it using Kafka, processes it using Spark, and stores it in Cassandra. Airflow is used for workflow management and Docker for containerization of the services.

# Setting Up
To set up this project, you need Docker and Docker Compose installed. Clone the repository, navigate to the project directory, and run docker-compose up. This will start all the necessary services.
