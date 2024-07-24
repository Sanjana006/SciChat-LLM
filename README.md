# SciChat-LLM-with-PDF-Support

SciChat-LLM is a powerful language model designed to enhance academic scientific discussions by supporting the use of PDF documents. It leverages advanced AI capabilities to provide insightful and context-specific answers to questions about academic and scientific literature. Whether you're exploring complex research papers or seeking information on general topics, SciChat-LLM offers thoughtful and accurate responses, making it an invaluable tool for students, researchers, and academics.

## Features

- **PDF Integration**: Upload and parse PDF documents to enable the model to provide accurate and relevant information based on the content.
- **Context-Aware Responses**: Generates responses that are informed by the content of the uploaded PDF documents.
- **Interactive Chat Interface**: A user-friendly chat interface for interacting with the language model.
- **Advanced Query Handling**: Handles complex scientific queries and provides detailed explanations.
- **General Question Support**: Answers general questions even without uploading any PDF, making it a versatile tool for various queries.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- Ollama and Mistral7b model
- Required Python packages (listed in `requirements.txt`)
- An environment capable of running large language models

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Sanjana006/SciChat-LLM.git
    cd SciChat-LLM
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Download Ollama & Mistral:
    ```sh
    Website: https://ollama.com/download
    ollama pull mistral:instruct
    ```

### Usage

1. Run Ollama model:
   ```sh
    ollama run mistral:instruct
    ```
   
2. Add the pinecone API key and environment name in app.py
   
3. Run the application:
    ```sh
    python app.py
    ```

4. Upload a PDF document through the interface (optional).

5. Start asking questions related to the content of the uploaded PDF or any general questions.
