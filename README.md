# Fullstack Chatbot - Public Repository

This repository contains the documentation and high-level overview of the Fullstack Chatbot project. Due to the private nature of the code, this public repository serves as a reference for understanding the architecture, technologies used, and implementation details. 


<img width="1105" alt="SCU Chatbot frontend (2)" src="https://github.com/user-attachments/assets/c48b8e6f-0b38-4253-b7c6-5f55e26011b2">



## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Fullstack Chatbot is an advanced conversational AI system designed to interact with users through a web interface. It leverages a custom language model (LLM) flow, Retrieval-Augmented Generation (RAG), and LangChain to provide contextually rich and accurate responses. The chatbot supports streaming responses for real-time interaction.

## Features

- **Responsive Frontend:** Built with Next.js and React, providing a smooth and dynamic user experience.
- **Scalable Backend:** Developed using Django with ASGI support, enabling high concurrency and real-time communication.
- **Custom LLM Flow:** Integrates a custom language model pipeline tailored for specific conversational contexts.
- **RAG Integration:** Enhances the chatbot's responses with relevant information retrieval.
- **Streaming Responses:** Real-time streaming of responses for seamless conversation.
- **Webhooks:** Utilized for triggering events and processing asynchronous tasks.

## Technologies Used

### Frontend
- **Next.js:** A React framework for server-side rendering and static site generation.
- **React:** JavaScript library for building user interfaces.
- **Webhooks:** For handling asynchronous events and communication between the frontend and backend.

### Backend
- **Python Django:** A high-level Python web framework for rapid development and clean, pragmatic design.
- **ASGI (Asynchronous Server Gateway Interface):** For handling asynchronous tasks and real-time data streaming.
- **LangChain:** Framework for developing applications powered by large language models.
- **RAG (Retrieval-Augmented Generation):** Combines language models with information retrieval for more accurate responses.

### Database
- **Database Integration:** Django's ORM for interacting with a relational database (e.g., PostgreSQL, MySQL, SQLite).

## Architecture

The Fullstack Chatbot is composed of the following key components:

- **Frontend:** Next.js application with React components, handling user interactions and sending requests to the backend via webhooks.
- **Backend:** Django application that processes requests, manages the database, and interacts with the custom LLM and RAG systems.
- **ASGI Server:** Facilitates real-time communication and streaming responses between the backend and frontend.
- **Custom LLM Flow:** Tailored language model pipeline integrated with RAG for enhanced conversational capabilities.

## Usage

Once the setup is complete, you can access the chatbot by navigating to `http://localhost:3000` in your web browser. Interact with the chatbot and observe the real-time responses powered by the custom LLM flow and RAG.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: This is a public repository for reference purposes only. The actual code is hosted in a private repository due to its proprietary nature.*
