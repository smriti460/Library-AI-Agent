# 📚 Library AI Agent

Overview

The Library AI Agent is an intelligent assistant developed using IBM watsonx Orchestrate, IBM watsonx.ai, and IBM Granite Models. The system helps students discover relevant books and learning resources through natural language interactions.

The agent uses Retrieval-Augmented Generation (RAG) to retrieve information from a library knowledge base and provide accurate responses related to books, authors, subjects, availability status, and semester-wise recommendations.

---

## Problem Statement


The objective of this project is to assist students in finding suitable learning materials based on their academic needs. The agent can search books, recommend resources, check availability, and provide personalized suggestions.

---

## Features

* Natural Language Book Search
* Author-Based Search
* Subject-Wise Book Recommendations
* Semester-Wise Book Recommendations
* Book Availability Checking
* Knowledge Base Retrieval using RAG
* AI-Powered Responses using IBM Granite Models
* Interactive Chat Interface

---

## Technology Stack

* IBM watsonx Orchestrate
* IBM watsonx.ai
* IBM Granite Models
* IBM Cloud
* Retrieval-Augmented Generation (RAG)
* Knowledge Base
* Microsoft Excel Dataset

---


---

## Dataset Structure

The library dataset contains:

* Book ID
* Book Title
* Author Name
* Subject
* Availability Status
* Semester

Example:

| Book ID | Title                    | Author               | Subject | Availability 
| ------- | ------------------------ | -------------------- | ------- | ------------ 
| B001    | Database System Concepts | Abraham Silberschatz | DBMS    | Available    

---

## Sample Queries

* Show me DBMS books
* Find books written by Abraham Silberschatz
* Show Artificial Intelligence books
* Check availability of Database System Concepts

---

## Project Workflow

1. Student enters a query.
2. The agent retrieves relevant information from the knowledge base.
3. RAG fetches matching content from the dataset.
4. IBM Granite Model generates an intelligent response.
5. The response is displayed to the student.

---

## Benefits

* Saves student time
* Improves access to learning resources
* Provides personalized recommendations
* Enhances library resource utilization
* Supports academic learning and research

---

## Future Scope

* Book Reservation System
* Waitlist Management
* Voice-Based Search
* Multilingual Support
* Real-Time Library Management System Integration

---

