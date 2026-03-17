# AI-Technician-Trainer
An AI application that helps manufacturing technicians learn complex assembly workflows

## The Problem

In manufacturing environments, technicians often need to assemble multiple product types while working across different shifts. Training materials are usually long technical manuals, making it difficult to quickly understand assembly steps or resolve questions during production.
This project explores how **Generative AI and Retrieval-Augmented Generation (RAG)** can simplify technician training by converting technical documentation into interactive learning and support tools.

## The Solution

AI Technician Trainer provides two core capabilities:

### 1. Training Module

- Converts long assembly manuals into concise step-by-step instructions
- Generates dynamic quiz questions to verify technician understanding
- Tracks technician scores for training and workforce management

### 2. Q&A Module

- Allows technicians to ask questions directly about the documentation
- Uses a RAG pipeline to retrieve relevant information from manuals
- Supports voice input and in any language and gives responses in same language for accessibility

## Example Demo

The demo simulates training for four server assembly workflows:
- Server A
- Server B
- Server C
- Server D

A technician can:
1. Select a server
2. Generate AI-based training instructions
3. Take a quiz to verify understanding
4. Ask questions about the assembly process

## Tech Stack

- Python
- Retrieval-Augmented Generation (RAG)
- Large Language Models
- Document chunking and vector retrieval
- Gradio (interactive UI)
- Pandas (training score tracking)

## Architecture

The AI Technician Trainer uses a Retrieval-Augmented Generation (RAG) pipeline to convert technical documentation into training summaries, quizzes, and interactive Q&A support.

<img width="573" height="623" alt="image" src="https://github.com/user-attachments/assets/fb31f3e1-2234-4622-a4bd-9f7001d95fcf" />


## Running the Project

- Install dependencies:
pip install -r requirements.txt

- Open and run the notebook in Jupyter:
AI_Technician_Trainer.ipynb


## Future Improvements

- Integration with database/ERP systems to store training records
- Have another module for admins to upload new training documents
- Have a login system, which determines the roles of the person and accordingly give admin/ user priviledges


## Demo

Demo video: [(LinkedIn video URL)](https://www.linkedin.com/posts/shabeeha-ahmed_generativeai-rag-aiinmanufacturing-activity-7439781794964508672-5DfI?utm_source=share&utm_medium=member_desktop&rcm=ACoAABs2ukMBbo5XHW47pdtSUDXQCLYPZE3RJHg)

---

## Author

Shabeeha Ahmed

This project demonstrates how AI can improve workforce training by transforming static documentation into interactive learning tools.
