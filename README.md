# Tagore_GPT

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-6.4.0-orange.svg)](https://jupyter.org/install)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT%203.5%20Turbo-5254E6.svg)](https://openai.com/)
[![Llama Index](https://img.shields.io/badge/Llama%20Index-1.0.0-green.svg)](https://llamaindex.com/)
[![langchain](https://img.shields.io/badge/langchain-0.1.0-yellow.svg)](https://github.com/your-username/langchain)

This project is a ChatGPT-powered chatbot trained on resources and documents related to Rabindranath Tagore, the renowned poet and philosopher from Calcutta, India. The aim of the project is to create a chatbot that can generate responses in the style of Rabindranath Tagore, providing an immersive experience for users who interact with it.

## TL;DR

Tagore_GPT is a ChatGPT-based chatbot trained on Tagore's literature. It uses Llama Index for document indexing and GPT 3.5 Turbo for generating responses. The project provides a unique opportunity to engage with Tagore's work through an AI-powered conversational interface.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Rabindranath Tagore, also known as Gurudev, was a polymath who made significant contributions to Bengali literature, music, art, and education. His works continue to inspire people worldwide. The Tagore_GPT project aims to capture the essence of Tagore's writings and create a chatbot that can mimic his style and persona.

To achieve this, the following tools and technologies were utilized:

- [Llama Index](https://llamaindex.com/): A powerful document indexing tool used to create an index vector database of PDF documents.
- Python: The programming language used to develop the chatbot.
- Jupyter Notebook: An interactive development environment used for coding and experimentation.
- [langchain](https://github.com/your-username/langchain): LangChain is a Python library that simplifies the creation of applications using large language models (LLMs)
- [OpenAI GPT 3.5 Turbo](https://openai.com/): A state-of-the-art language model used for generating text responses based on input prompts.
- JSON Scripts: Used to manage and process data.

## Project Structure

The project repository has the following structure:

```
Tagore_GPT/
├── data/
│   ├── document1.pdf
│   ├── document2.pdf
│   └── ...
├── Tagor_GPT.ipynb
└── requirements.txt
```

The `data` directory contains the PDF files that were web scraped to collect Tagore's documents. The `Tagor_GPT.ipynb` notebook is the main program that contains the code for training the model and generating responses. The `requirements.txt` file lists the Python dependencies required to run the notebook.

## Installation

To run the Tagore_GPT chatbot locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/avikshit-banerjee/Tagore_GPT.git
cd Tagore_GPT
```

2. Create a virtual environment (optional but recommended):

```bash
python3 -m venv env
source env/bin/activate  # For Linux/Mac
.\env\Scripts\activate  # For Windows
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the `Tagor_GPT.ipynb` notebook in Jupyter Notebook.

```bash
jupyter notebook Tagor_GPT.ipynb
```

2. Follow the instructions in the notebook to train the model and generate responses.

3. Customize the prompt and query prompts to explore different aspects of Tagore's work.

4. Interact with the chatbot by providing prompts and receiving responses generated in the style of Rabindranath Tagore.

## Contributing

Contributions to this project are welcome. If you have any ideas, suggestions, or improvements, please follow these steps:

1. Fork the repository.

2. Create a new branch.

3. Make your changes and enhancements.

4. Test your changes.

5. Submit a pull request.

Please ensure that your contributions align with the project's goals and adhere to the existing coding style and guidelines.

## License

The Tagore_GPT project is licensed under the [MIT License](LICENSE).

---

Thank you for your interest in the Tagore_GPT project. We hope you enjoy interacting with the chatbot and experiencing the writings of Rabindranath Tagore in a unique way. If you have any questions or feedback, please don't hesitate to reach out.
