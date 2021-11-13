# Hostel Management System

***A system to manage the infrastructure and students of a hostel***

## Development

### Clone the repository
> Make sure to have the latest version of node and npm installed

```bash
git clone https://github.com/Yashi002/Hostel_M.git
cd Hostel-Management-DBMS-Project
npm install
```  

### Setting up the database

```bash
psql
create database hosteldb;
create user hosteluser with encrypted password 'hostelpass';
grant all privileges on database hosteldb to hosteluser;
```
> To login as the hosteluser

```bash
psql -d  hosteldb -U hosteluser
``` 

### Run the app

```bash
npm start
```

Server will start running on http://localhost:8888
