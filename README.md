# Software Engineering Principles (SENG8091)

## Assignment 3 : Actionable Items

### Student Information:
- **Name:** Urvi Surti  
- **Student ID:** 8993413  

## Project Overview:
This project focuses on implementing a system to collect, process, and manage question-answer data from web sources. The system includes functionalities such as data extraction, storage, standardization, duplicate removal, bias detection, data balancing, monitoring, security, and stakeholder feedback. The repository contains the necessary scripts and database schema to achieve these objectives.

## Requirements and Features:

### 1: As a developer, creating a system where collecting data from web helps to differentiate questions from answers.
- **Priority:** High
- **Assumptions:** 
    - Extracting data can help to collect questions and answers from various sources with sorted data
    - The information collected from web prefers HTML and CSS to differentiate between questions and answers 
- **Validations:**
    - Is there any system that differentiates between questions from answers with all entries?
    - Is there any system that confirms the missed part of  question and answer ?
- **Tasks:**
    - Identify and access websites which handles sorted question-answer data.
    - Implement logic to differentiate between questions and answers based on HTML elements and CSS styles
    - Store information temporarily to ensure question and answer are differentiated correctly
    - Test and validate the information to confirm correct categorization of data
- **Actionability:**
    - This task will ensure that correct data are collected and differentiated. It is actionable with data extracting and testing tools

### 2: As a developer, creating a database helps to store questions and answers separately but linkified
- **Priority:** High
- **Assumptions:** 
    - A database can handle relational data and supports indexing for quick retrieval of data
    - A database has a unique identifier for linking question and answer pair together
- **Validations:** 
    - Does a database store question and answer in different table ?
    - Does a database maintain links between question and answer ?
- **Tasks:** 
    - Design a database schema with different tables for questions and answers
    - Define relations between tables using primary/foreign key 
    - Set up a test dataset to ensure correct storage and linking
    - Set up indexing to enhance speed and query performance 
- **Actionability:**  
    - This task will ensure that correct technical implementation carries out for storing and linking data. It is actionable with setup of a relational database system and appropriate table design.

### 3: Creating a standard format to ensure that analysis of data is easier and quicker.
- **Priority:** Medium
- **Assumptions:** 
    - The data is standardized to a format that can be easily processed like JSON or CSV
    - The data can be formatted in a way that question types and categories are logical 
- **Validations:** 
    - Is the data logical for all entries?
    - Does the standardized data format support all types of analysis and data processing tasks?
- **Tasks:** 
    - Define a standardized format for data storage (e.g., CSV with specific fields for question, answer, and category).
    - Implement scripts to convert data into standardized format after extracting or categorizing.
    - Review the data to ensure defined format is followed 
    - Modify the format structure where necessary changes meet s
- **Actionability:**  
    - This task will ensure that data remains logical and easy to analyze. It is actionable by creating a template and testing if the data matches the format for all entries.

