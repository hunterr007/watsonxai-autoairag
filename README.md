# Watsonx.ai

- Provide Prompt Lab
  Chat and build prompts with foundation models 
- Agent Lab (Beta)
  Create AI Agents
- Tuning Studio
  Tune model with foundation data
 
## Prompt Lab
Provide 3 different modes-
1. Chat
   Designed for conversational interactions, mimicking a dialogue.
   Maintains a history of the conversation, allowing the model to build upon previous turns.
3. Structured
   Facilitates the creation of prompts with a defined structure, often used for "few-shot prompting."
   Provides fields for "instruction," "examples," and "test input."
   Enables users to provide examples of desired input-output pairs, guiding the model's behavior.
5. Freeform
   Offers maximum flexibility, allowing users to write prompts in plain text.
   Suitable for users who are comfortable with prompt engineering and require precise control over the input.
 
![mermaid-diagram-2025-03-05-015629](https://github.com/user-attachments/assets/e73a09bb-3614-44eb-b7c7-f6601ac6e7b0)

## AI Guardrail
AI guardrails are essential mechanisms designed to ensure that artificial intelligence systems operate within ethical, legal, and technical boundaries.
They help with-
- Preventing Bias
- Promoting Responsible Use
- Preventing Harmful Outputs
- Controlling Hallucinations
- Protecting Sensitive Data
- Adhering to Regulatory Standards/Compliance
- Building Trust and Transparency


# Watsonx Auto AI RAG
Auto AI RAG setup by Watsonx.ai

## RAG vs AutoAI RAG

### RAG
RAG enhances large language models (LLMs) by enabling them to retrieve relevant information from external data sources before generating a response.
- To improve the accuracy and reliability of LLM responses by grounding them in factual data.
- To enable LLMs to access and utilize up-to-date information beyond their training data.

This process involves:
- Retrieving relevant documents or data based on a user's query.
- Providing that retrieved information to the LLM.
- The LLM then uses this information to generate a more accurate and contextually appropriate answer.

### AutoAI RAG
AutoAI RAG automates the process of optimizing RAG pipelines. It is an automation layer built on top of RAG with focuse on optimizing the RAG process itself.
- It uses automated machine learning (AutoML) techniques to find the best configuration for a RAG system based on specific data and use cases.
- It also provides a streamlined process for deploying optimized RAG solutions.

This process involves:
- To simplify and accelerate the development and deployment of effective RAG systems.
- To improve the performance of RAG applications by automatically finding the best configurations.
- To reduce the amount of expert knowledge needed to create effective RAG pipelines.

Below diagram explains the difference between RAG vs AutoAI RAG-

![Untitled diagram-2025-03-04-161641](https://github.com/user-attachments/assets/db5d7a2e-3d5e-4af3-b845-0370659c3da4)



## Run Milvus on Cloud
Setup Zilliz Cloud and create database-

![image](https://github.com/user-attachments/assets/c44a534b-1f9a-49a7-8469-6ff6d0d8608e)

