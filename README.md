# Multi-Source-QA-AI-Engine

## Overview

The Multilingual Q&A Enhancer is a powerful question-answering application designed to provide users with dynamic and up-to-date insights beyond the limitations of traditional language models. Leveraging advanced technologies such as Long Language Models (LLM), Python, LangChain, OpenAI, and Pinecone, this project allows users to extract answers from various data formats, including custom files and public datasets. It offers multilingual support, smart chunking, and seamless translation capabilities to enhance the user experience.

## Project Components

### 1. Data Preprocessing and Embedding

The uploaded data is initially transformed into long-chain documents and then segmented into smaller, more manageable chunks. These chunks are converted into numeric vectors using embedding techniques, which capture the semantic meaning of the text. The chunks and their corresponding embeddings are stored in a vector database using Pinecone.

### 2. Question-Chunk Similarity Ranking

When a user submits a question, the question itself is embedded into a numeric vector. The project employs advanced algorithms to rank the numeric vectors representing the text chunks based on their similarity to the question embedding. This ranking ensures that the most relevant chunks are identified, enhancing the accuracy of the answers provided.

### 3. GPT-Assisted Answer Generation

The project sends the most relevant chunks along with the user's question as a message to a GPT model. The GPT model processes the input message and generates a coherent and contextually appropriate answer. This answer is then returned to the user, addressing their inquiry effectively.

## Key Features

### 1. Post-2021 Insights

By integrating OpenAI's LLM and Pinecone, the Multilingual Q&A Enhancer overcomes the limitations of GPT models in providing answers beyond September 2021. Users can obtain fresh insights and information, catering to real-time data needs.

### 2. Diverse Data Format Support

The application offers a user-friendly interface to upload custom files stored in various formats, such as HTML, CSV, PDF, and more. Additionally, it seamlessly retrieves information from popular public and proprietary datasets like Wikipedia, arXiv, and Twitter.

### 3. Multilingual and Translation Capabilities

This project supports multiple languages, enabling users to ask questions in their preferred language. Furthermore, the translation feature allows questions to be seamlessly translated into other languages, broadening the reach and utility of the application.

### 4. Contextual Querying

The intelligent chunking and ranking system ensures that users receive contextually relevant answers. Users can ask questions consecutively, and the application maintains a seamless context, providing accurate answers based on previous interactions.

### 5. Smart Chunking for Optimal Relevance

Utilizing LangChain, the application employs chunking to break down large pieces of text, optimizing the relevance of search results from the vector database. This process enhances the accuracy of answers and provides a more focused user experience.

## Getting Started

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using your jupyter notebook.
4. Access the application through your web browser at `http://localhost:5000`.

## Conclusion

The Multilingual Q&A Enhancer project presents a sophisticated solution for users seeking real-time information across various data formats and languages. Its innovative approach to chunking, embedding, and GPT-assisted answer generation empowers users to access timely insights and answers in a user-friendly and seamless manner.

For more information and technical details, please refer to the documentation included in this repository.

---

