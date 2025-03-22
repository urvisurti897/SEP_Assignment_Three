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

### 4: As a developer, creating a system that removes duplicates to enhance data quality
- **Priority:** High
- **Assumptions:** 
    - The data can be duplicated while collecting or categorizing data
    - The duplicated data removal process will be automated to eliminate the need for manual work 
- **Validations:** 
    - Are all duplicates correctly identified and removed from the database?
    - Is the data quality improved by removing duplicates without loss of critical information?
- **Tasks:** 
    - Implement an algorithm to identify duplicate questions and answers based on content
    - Use hashing or similar metrics to detect and eliminate same or near-duplicate data entries.
    - Test the system to ensure no important unique data is mistakenly removed.
    - Set up a process for regularly checking for new duplicates as more data is collected.
- **Actionability:**   
    - This task will ensure that data quality is mandatory. It is actionable by implementing automated tools to verify and eliminate duplicate entries.

### 5: As a developer, utilizing tools to verify biases in data
- **Priority:** High
- **Assumptions:** 
    - The dataset is big enough to require advanced algorithms for detecting bias 
    - The AI models have already been trained or are in development, and bias detection tools are needed to assess the quality of data inputs
- **Validations:** 
    - Are the current algorithms capable of detecting different biases such as demographic bias or representation bias?
    - Have we validated the findings from the bias detection tools with domain experts?
- **Tasks:** 
    - Identify potential bias factors such as race, gender, etc in the dataset.
    - Implement advanced statistical methods like fairness factors and correlate tests to assess bias.
    - Document and report the identified biases and its impact on model performance.
    - Work with domain experts to clarify bias results and recommend corrective actions.
- **Actionability:**  
    - This task will ensure that tools is useful to detect biases in data. It is actionable by implementing automated tools to verify and eliminate duplicate entries.

### 6: Creating balanced data so that all groups are equally represented 
- **Priority:** Medium
- **Assumptions:** 
    - The dataset has imbalanced groups that leads some groups being overrepresented or underrepresented
    - The aim is to ensure a balanced representation across all key categories before model training
- **Validations:** 
    - Have we identified which groups are underrepresented or overrepresented in the dataset?
    - Have we validated tested the performance of the model after applying balancing techniques like oversampling or under sampling?
- **Tasks:** 
    - Identify underrepresented and overrepresented categories in the dataset.
    - Use oversampling for groups that are underrepresented, or under sampling that are overrepresented. 
    - Make sure the data balancing process doesn't alter important patterns in the data. 
    - Test the model's performance with the balanced data to check for improvement.
- **Actionability:** 
    - This task will ensure that using oversampling or under sampling techniques on the dataset. It is actionable by balancing dataset and monitor model's performance after enhancement.

### 7: Creating split format to keep data balanced 
- **Priority:** High
- **Assumptions:** 
    - The dataset contains different categories that requires equal presentation  in all subsets 
- **Validations:** 
    - Are the splits logical and uniform across different subsets such as training, testing or validation?
- **Tasks:** 
    - Identify the most important categories that requires balanced representation across the datasets.
    - Split the data into training, validation, and test sets while maintaining the balance. 
    - Test for distribution imbalances in subsets individually.
- **Actionability:** 
    - This task will ensure that splitting data across subsets requires maintenance. It is actionable by ensuring no group is over- or under-represented in the final data split.

### 8: As a developer, implementing regular monitoring for biases
- **Priority:** Ongoing
- **Assumptions:** 
    - The model and dataset changes over time that makes continuous monitoring mandatory
    - Regular checks for bias are mandatory to identify any emerging issues after model deployment or during retrieval.
- **Validations:** 
    - Do we have a continuous monitoring plan in place to track emerging biases over time?
    - Are we using real-time data or periodic reviews to assess bias in the dataset?
- **Tasks:** 
    - Set up a regular review schedule to monitor biases in the dataset 
    - Develop automated tools to detect emerging biases in real-time.
    - Create a feedback loop for correcting biases when detected in the dataset.
    - Report any new bias issues and collaborate with teams to mitigate them.
- **Actionability:** 
    - This task will ensure that implementing real-time or periodic data are monitored. It is actionable by ensuring corrective actions are taken promptly.

### 9: Checking collected data from web is accurate, relevant and meets the AI model requirements.
- **Priority:** High
- **Assumptions:** 
    - The web data is sourced from reputable platforms with relevant content.
    - AI model requirements are well-defined, with clear parameters for acceptable data quality.
- **Validations:** 
    - Is the data relevant to the AI model’s principle?
    - Is there any discrepancy between the data and the AI model's requirements?
- **Tasks:** 
    - Review the data collection criteria.
    - Implement automated checks for data consistency.
    - Conduct manual inspections to ensure accuracy.
    - Log any issues or discrepancies for further investigation.
- **Actionability:** 
    - This task will ensure that verifying collected data is accurate, relevant and meets the AI model requirements. It is actionable by ensuring manual inspections has assured quality.

