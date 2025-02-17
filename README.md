## **🚀 My Role in the Project**  

I contributed to this project as a **Data Engineer**, focusing on **building and optimizing data pipelines, preprocessing data, and designing the database structure.**  

### **Key Contributions:**  
- **Developed ETL Pipelines** → Collected and processed **workout & gym metadata** using **Python & SQL**  
- **Database Design & Management** → Designed and optimized **PostgreSQL** schema for efficient data storage and retrieval  
- **Data Preprocessing** → Implemented **automated data transformation workflows** for structured data analysis  
- **Integration with External APIs** → Built **data synchronization** pipelines fetching real-time exercise & gym data from APIs  
- **Deployed REST APIs with PythonAnywhere** → Configured and managed **REST API** endpoints using PythonAnywhere for stable API operations
- **Automated Data Synchronization** → Utilized **Apache Airflow** to schedule and manage data updates efficiently  
- **Collaboration & Documentation** → Managed technical documentation and **coordinated team efforts using Notion & Zep**  

---

# FitSync

**FitSync** is a platform that integrates and manages **PT records, workout data, authentication, and metadata** between trainers and clients. This project is designed to help **gyms and trainers communicate effectively with their clients and manage data efficiently**.

---

## **📌 Project Overview**

FitSync was developed with the following objectives:

- Supporting **effective communication** between trainers and clients
- Structuring **PT records and workout data management**
- Integrating **authentication and metadata** to improve operational efficiency

---

## **🚀 Key Features**

1. **Workout Metadata Management**
   - Manage workout names, target muscles, primary/secondary muscle groups, workout images, etc.
2. **Trainer-Client Relationship Management**
   - Connect trainers and clients and manage PT records.
3. **PT Record Storage & Retrieval**
   - Record and manage data such as sets, repetitions, and weights.
4. **OCR-Based PT Record Generation via Camera**
   - Automatically recognize and recommend the most relevant workout metadata.
5. **S3 & RDS Integration**
   - Utilize **AWS S3 for file storage** and **AWS RDS for data management**.
6. **Automated Data Synchronization**
   - Use **Apache Airflow** for scheduled data synchronization and updates.

---

## **🛠 Prerequisites**

- Python 3.10 or later
- PostgreSQL 13 or later
- AWS account and S3 bucket setup
- Docker & Docker Compose

---

## **💾 Database & DAG Features**

1. **Workout Data Synchronization**
   - Fetch **ExerciseDB** data via API and synchronize with **S3 and RDS**.
   - Link: [https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb)

2. **Trainer-Client Connection**
   - Manage trainer-client relationships and PT scheduling.

3. **Data Visualization**
   - Manage and analyze client PT records.

4. **Gym Data Synchronization**
   - Fetch **Seoul Gym Data** via API and synchronize with **S3 and RDS**.
   - Link: [https://data.seoul.go.kr/dataList/OA-16142/A/1/datasetView.do](https://data.seoul.go.kr/dataList/OA-16142/A/1/datasetView.do)

---

## **📂 Database Structure**

- **Schema**: **`raw_data`**
  - `exercise`: Workout metadata table
  - `customer`: Client information
  - `trainer`: Trainer information
  - `pt_record`: PT record table
  - `pt_record_exercise`: PT record & exercise linking table
  - `pt_schedule`: PT schedule table
  - `gym_metadata`: Gym metadata table

- **Schema**: **`credential`**
  - `user_auth`: User authentication information

---

## **⚙ Technology Stack**

<div style="display: flex; gap: 10px;">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=plastic" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=plastic" />
  <img alt="Flask" src="https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff&style=plastic" />
  <img alt="PythonAnywhere" src="https://img.shields.io/badge/PythonAnywhere-1D9FD7?logo=pythonanywhere&logoColor=fff&style=plastic" />
  <img alt="AWS" src="https://img.shields.io/badge/Amazon%20Web%20Services-232F3E?logo=amazonwebservices&logoColor=fff&style=plastic" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=plastic" />
  <img alt="Apache Airflow" src="https://img.shields.io/badge/Apache%20Airflow-017CEE?logo=apacheairflow&logoColor=fff&style=plastic" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=plastic" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=fff&style=plastic" />
</div>

---

## **📧 Contact**

- Email: [onedersea@gmail.com](mailto:onedersea@gmail.com)
