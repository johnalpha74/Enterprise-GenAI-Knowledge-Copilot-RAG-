# Enterprise-GenAI-Knowledge-Copilot-RAG-
An enterprise-grade Generative AI knowledge copilot that answers user questions over internal documents (policies, SOPs, contracts) using Retrieval-Augmented Generation (RAG) on AWS.  This project demonstrates LLM orchestration, secure retrieval, governance, and explainability in production environments.

🎯 Objectives

Build a production-ready GenAI system using RAG

Reduce hallucinations through grounded retrieval

Provide transparent, explainable AI responses

🧠 Architecture

User → API Gateway → Lambda

Amazon Bedrock (LLM inference)

OpenSearch (Vector Search)

S3 (Document Store)

☁️ AWS Services Used

Amazon Bedrock

Amazon OpenSearch (Vector Engine)

AWS Lambda

Amazon S3

API Gateway

IAM, CloudWatch

🔍 Explainability & Trust

Source document attribution

Confidence scoring per response

Retrieval traceability
