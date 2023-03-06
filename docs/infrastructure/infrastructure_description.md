# Infrastructure Description

- Postgres Database hosted at **RDS** (Relational Database Service) save and display data
- Backend Server On **EB** (Elastic Beanstalk)
- Frontend Hosted at **S3** (Simple Storage Service)

The user open the frontend app -> Frontend app request/send data to backend server -> Backend server store/retrieve these data using RDS Database
