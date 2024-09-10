# Digital E Gram Panchayat

# Project Overview

Digital E Gram Panchayat is a web-based platform developed using JSP (JavaServer Pages) to digitize and streamline the operations of Gram Panchayats in India. This project aims to improve transparency, accountability, and efficiency in rural governance.

A system to implement Operations on MYSQL Database

# Features

- User authentication and authorization for Gram Panchayat members and officials
- Digital record-keeping and management of meeting minutes, decisions, and documents
- Automated workflows for various Gram Panchayat processes and services
- Data visualization and analytics for informed decision-making
- Integration with existing government databases and systems

# Technologies Used

- Frontend: JSP, HTML, CSS, JavaScript
- Backend: Java, MySQL
- Server: Apache Tomcat

# Database Schema

The MySQL database schema consists of the following tables:

- users: stores user information (username, password, role)
- meetings: stores meeting details (date, time, agenda, minutes)
- decisions: stores decision details (meeting_id, decision_text, status)
- documents: stores document details (meeting_id, document_name, file_path)

# SQL Queries

- CREATE TABLE users (username VARCHAR(50), password VARCHAR(50), role VARCHAR(10))
- CREATE TABLE meetings (meeting_id INT PRIMARY KEY, date DATE, time TIME, agenda TEXT, minutes TEXT)
- CREATE TABLE decisions (decision_id INT PRIMARY KEY, meeting_id INT, decision_text TEXT, status VARCHAR(10))
- CREATE TABLE documents (document_id INT PRIMARY KEY, meeting_id INT, document_name VARCHAR(50), file_path VARCHAR(100))

# Tomcat Server Configuration

- Deploy the WAR file on Apache Tomcat Server
- Configure the context.xml file to point to the MySQL database
- Start the Tomcat Server to serve the application

# Usage

1. Register as a Gram Panchayat member or official
2. Log in to access the dashboard and features
3. Explore the various modules and tools

# Contributing

1. Fork the repository: `git fork (link unavailable)
2. Create a new branch: git checkout -b your-branch-name
3. Make changes and commit: git commit -m "Your commit message"
4. Open a pull request


# Contact

- Email: lakshman562000@gmail.com
- GitHub: https://github.com/lakshman562000
- Linkedin: https://www.linkedin.com/in/lakshman-chaudhary-4532061ba/