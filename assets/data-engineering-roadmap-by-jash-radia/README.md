# Data Engineering Roadmap

This roadmap visualizes the complete learning path for data engineering, from prerequisites through core tools and projects.
[This diagram is based on the Data Engineering Roadmap by Jash Radia](index.pdf)

## Roadmap Diagram

```mermaid
graph TD
    Start[Data Engineering Roadmap] --> Prerequisites[Prerequisites]
    
    Prerequisites --> P1[DBMS and SQL<br/>Hands On]
    Prerequisites --> P2[Python<br/>Hands On]
    Prerequisites --> P3[Linux]
    
    P1 --> EverythingData[Everything Data]
    P2 --> EverythingData
    P3 --> EverythingData
    
    EverythingData --> ED1[Data Warehouse<br/>Course or Book]
    EverythingData --> ED2[Research: Data Lake,<br/>Data Mart, Data Fabric,<br/>Data Mesh, Data Catalog, etc.]
    
    ED1 --> DistributedSystems[Distributed Systems]
    ED2 --> DistributedSystems
    
    DistributedSystems --> DS1[Spark with Python<br/>Course or Hands On]
    DistributedSystems --> DS2[Research: Basics about<br/>Hadoop, Hive, Pig,<br/>MPP systems]
    
    DS1 --> Cloud[Cloud]
    DS2 --> Cloud
    
    Cloud --> C1[GCP or AWS or Azure]
    Cloud --> C2[Consider Certifications:<br/>AWS Solutions Architect,<br/>AWS Big Data Specialty,<br/>GCP Professional Data Engineer,<br/>Azure Cloud Fundamentals, etc.]
    
    C1 --> MustLearnTools[Must Learn Tools]
    C2 --> MustLearnTools
    
    MustLearnTools --> MLT1[Orchestration:<br/>Airflow]
    MustLearnTools --> MLT2[Compute:<br/>Databricks and Snowflake<br/>Substitutes: AWS EMR or<br/>GCP Dataproc or AWS Redshift<br/>or GCP BigQuery]
    MustLearnTools --> MLT3[CICD:<br/>Jenkins and Sonarqube]
    MustLearnTools --> MLT4[Streaming:<br/>Kafka]
    MustLearnTools --> MLT5[Containers:<br/>Docker]
    
    MLT1 --> Projects[Projects]
    MLT2 --> Projects
    MLT3 --> Projects
    MLT4 --> Projects
    MLT5 --> Projects
    
    Projects --> Proj1[Batch Processing]
    Projects --> Proj2[Real Time Processing]
    Projects --> Proj3[Create free tier account<br/>in AWS, GCP or Azure<br/>Implement end-to-end projects]
    
    Proj1 --> Optional[Additional Optional Topics]
    Proj2 --> Optional
    Proj3 --> Optional
    
    Optional --> Opt1[Building, Training and<br/>Deploying ML Models]
    Optional --> Opt2[Data Visualization:<br/>Tableau or Power BI or Looker]
    Optional --> Opt3[ETL/ELT: Matillion or Talend]
    Optional --> Opt4[Containers: Kubernetes]
    Optional --> Opt5[Pick any tool or topic<br/>and deep dive further!<br/>Be an SME in one topic]
    
    style Start fill:#e1f5ff,stroke:#01579b,stroke-width:3px
    style Prerequisites fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style EverythingData fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style DistributedSystems fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style Cloud fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style MustLearnTools fill:#e8f5e9,stroke:#1b5e20,stroke-width:2px
    style Projects fill:#fff3e0,stroke:#e65100,stroke-width:2px
    style Optional fill:#f3e5f5,stroke:#4a148c,stroke-width:2px
```

## Key Components

### 1. Prerequisites
- **DBMS and SQL**: Hands-on experience required
- **Python**: Hands-on experience required
- **Linux**: Fundamental knowledge

### 2. Everything Data
- **Data Warehouse**: Learn through courses and books
- **Research**: Data Lake, Data Mart, Data Fabric, Data Mesh, Data Catalog, etc.

### 3. Distributed Systems
- **Spark with Python**: Course and hands-on practice
- **Research**: Basics about Hadoop, Hive, Pig, MPP systems

### 4. Cloud
- **Platforms**: GCP, AWS, or Azure
- **Certifications**: Consider AWS Solutions Architect, AWS Big Data Specialty, GCP Professional Data Engineer, Azure Cloud Fundamentals, etc.

### 5. Must Learn Tools
- **Orchestration**: Airflow
- **Compute**: Databricks and Snowflake (Substitutes: AWS EMR or GCP Dataproc | AWS Redshift or GCP BigQuery)
- **CICD**: Jenkins and Sonarqube
- **Streaming**: Kafka
- **Containers**: Docker

### 6. Projects
- **Batch Processing**: Process large volumes of data in batches
- **Real Time Processing**: Master streaming data processing
- **Cloud Practice**: Create a free tier account in AWS, GCP, or Azure and implement end-to-end projects

### 7. Additional Optional Topics
- **ML Models**: Building, training, and deploying machine learning models
- **Data Visualization**: Tableau, Power BI, or Looker
- **ETL/ELT Tools**: Matillion or Talend
- **Containers**: Kubernetes
- **Specialization**: Pick any tool or topic and deep dive further to become a Subject Matter Expert (SME)
