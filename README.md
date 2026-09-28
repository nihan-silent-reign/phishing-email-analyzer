# phishing-email-analyzer
Python-based phishing email analysis and AI-assisted phishing knowledge system using RAG, chromaDB and Ollama 

This project is a Python-based phishing email detection and analysis system designed to identify suspicious characteristics in email messages and provide a risk/severity assessment.

The project also includes a web-based interface using Streamlit and an AI-powered Retrieval-Augmented Generation (RAG) assistant that can answer questions related to phishing and email security using a custom knowledge base.



**Key Features**

* Phishing email analysis
* Email header analysis
* SPF, DKIM and DMARC checks
* Suspicious URL detection
* Punycode detection
* Typosquatting detection
* Attachment analysis
* Social-engineering indicator analysis
* Risk/severity assessment
* Streamlit web interface
* RAG-based phishing knowledge assistant
* Local AI response generation using Ollama
* Vector similarity search using ChromaDB


**Technologies Used**

* Python
* Streamlit
* ChromaDB
* Ollama
* Retrieval-Augmented Generation (RAG)
* all-MiniLM-L6-v2 embedding model
* Email analysis libraries
* HTML/URL parsing



**System Architecture**

Phishing Email Analysis

Email (.eml)
     ↓
Python Email Analyzer
     ↓
Email Headers / URLs / Attachments
     ↓
Security Indicator Analysis
     ↓
Risk / Severity Assessment
     ↓
Results







**RAG-Based AI Assistant**

Phishing Knowledge Base (PDF)
              ↓
        Text Extraction
              ↓
          Text Chunks
              ↓
     all-MiniLM-L6-v2
              ↓
          ChromaDB
              ↓
        User Question
              ↓
      Similarity Search
              ↓
     Relevant Information
              ↓
            Ollama
              ↓
        AI-Generated Answer



**Web Application**

The phishing analysis functionality was integrated into a Streamlit-based web interface, allowing users to interact with the analysis system through a browser.



**AI-Powered Phishing Assistant**

The project includes a Retrieval-Augmented Generation (RAG) component.
A phishing knowledge base is converted into embeddings using the all-MiniLM-L6-v2 model and stored in ChromaDB. When a user asks a question, relevant information is retrieved from the vector database and provided to Ollama to generate a contextual response.



**Project Objectives**

* Understand common phishing indicators.
* Automate basic phishing email analysis.
* Identify suspicious email characteristics.
* Build a browser-based security analysis interface.
* Implement a RAG pipeline for phishing-related security questions.
* Gain practical experience with vector databases and local LLMs.


**Limitations**

This project is a cybersecurity learning and proof-of-concept project. 

Detection results depend on the indicators and analysis techniques implemented in the project.

The AI assistant’s responses depend on the knowledge base and local language model used.


**Future Improvements**

* Real-time email mailbox integration
* Advanced URL reputation checking
* Automated attachment sandboxing
* Integration with SIEM platforms
* Improved machine-learning-based phishing classification
* Additional threat-intelligence sources


 
 
 
 
 
 
 
 **Author**

Nihan Mhd

Cybersecurity Enthusiast | Security Analyst / SOC

This project was developed as part of my practical cybersecurity learning and portfolio development.
       


