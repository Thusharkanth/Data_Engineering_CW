#  Data Engineering Coursework

## 📝 Assessment Overview
**Module:** CM2606 Data Engineering  
**Deadline:** 18th April 2025
**Submission:**  
- Report  
- Video demonstration (for Question 1)  

**Key Skills Developed:**  
✅ Building ETL pipelines with Airflow  
✅ Data modeling (Star Schema)  
✅ Cloud security & compliance (HIPAA/GDPR)  

---

## 📂 Repository Contents

```bash
Data_Engineering_Coursework/
├── CM2606-CW-2025.pdf            # Original coursework brief
├── Data Engineering CW Report.pdf # Submitted report (contains all answers)
└── README.md                     # This overview file
```

## 🎥 Question 1: ETL Pipeline Demo
[![Video Thumbnail](https://img.youtube.com/vi/.../0.jpg)](https://drive.google.com/file/d/1cNqBaZgcviXH04R707QccRQ1BtKFB6UM/view)  
*Click image to watch the AWS Airflow implementation*

**Components Implemented:**  
- OpenWeather API extraction  
- Data transformation to Parquet/CSV  
- S3 loading with Airflow DAGs  
- Automated scheduling  

---

## 📊 Question 2: SuperMart Data Model
**Star Schema Components:**  
1. **Dimension Tables** 
2. **Fact Table**  
3. **Aggregate Tables**  

*Refer to report for diagram and other details *  

---

## 🔒 Question 3: Healthcare Security Framework

### 1. Authentication & Authorization
- Implement strong authentication (MFA/OAuth)
- Design granular authorization using:
  - Role-Based Access Control (RBAC) or
  - Attribute-Based Access Control (ABAC)

### 2. Data Protection
- **At-rest encryption**: AES-256 standard
- **In-transit encryption**: TLS 1.3
- **Sensitive data handling**:
  - Column-level security for PII
  - Dynamic data masking

### 3. Compliance Measures
- Implement audit trails (e.g., AWS CloudTrail)
- Establish data retention policies
- Real-time monitoring (SIEM solutions)

### 4. Third-Party Access
- Secure API gateway implementation
- Token-based authentication
- Rate limiting mechanisms
- Aggregated data exposure only

---
*Submitted by: [Loganthan Thusharkanth] (Student ID: [20233168])*  
