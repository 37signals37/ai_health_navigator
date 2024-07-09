# AI Health Navigator
Uses OpenAI's api backend to review ehr files and patient history and then answers questions and searches for clinical trials for patient

# Project Overview
This project is designed to securely anonymize and format electronic health records (EHR) for interaction with OpenAI's API, specifically for use with the ChatGPT model. The primary aim is to facilitate a safe and efficient way for healthcare providers and researchers to gain insights from EHR data using advanced AI-driven queries and analysis.

# Purpose
The health sector generates vast amounts of data that are underutilized due to privacy concerns and the complexity of the data. This project aims to bridge this gap by:

Anonymizing EHR: Ensuring that all EHR data used with the OpenAI API are anonymized to protect patient privacy according to HIPAA regulations.

Formatting Data: Converting EHR data into a format that is compatible with OpenAI's API, enabling seamless integration.

AI-Driven Insights: Allowing healthcare professionals to interact with the anonymized data through ChatGPT, asking questions and receiving AI-generated insights which can support clinical decision-making.

Clinical Trials Matching: Integrating a feature where ChatGPT checks a weekly updated list of available clinical trials and emails suggestions of suitable clinical trials to healthcare providers, based on the anonymized patient data.

# Key Features
Data Anonymization Module: Strips identifiable information from EHRs to maintain patient confidentiality.

Data Formatter: Transforms and preprocesses EHR data into a tokenized format that is compatible with the OpenAI API.

Query Interface: Facilitates easy interaction with ChatGPT, allowing users to ask specific questions about anonymized patient records.

Clinical Trials Matcher: Utilizes updated clinical trials information to find potential matches for patients based on their anonymized records and informs patients via email.

# Technologies Used
Python: Primary programming language for data processing and integration with OpenAI API.

OpenAI API: Powers the ChatGPT interactions for generating insights from EHR data.

Flask: For creating a web-based interface to interact with the system.

SMTP Protocol: For sending email notifications to healthcare providers.

# License

# Contact Me
For any inquiries or interest, please connect with Eric Brunner on [LinkedIn](https://www.linkedin.com/in/eric-brunner-18997b47)


