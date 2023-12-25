# Chat-GPT Clone : Fenil-GPT

A Chat-GPT clone project using React JS, Node JS, HTML, Tailwind CSS, and the OpenAI API, following a server-client architecture.

## Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Welcome to the Chat-GPT Clone project – a powerful and versatile chat application built with cutting-edge technologies. This project leverages React JS for the dynamic client-side interface, Node JS for the robust server backend, HTML for structured markup, Tailwind CSS for seamless styling, and integrates the OpenAI API for advanced natural language processing and utilization of OpenAI in the project.

# Fenil-GPT
![GUI](https://github.com/fenil210/Chat-GPT-Clone/assets/121050723/923dc92a-e66b-4a05-9746-36f3c8de0fbe)


# Interactive Conversations: 
Engage in dynamic conversations with the Chat-GPT model, offering a user-friendly and responsive interface.
# Real-time Updates: 
Experience real-time updates as the application seamlessly communicates between the React JS client and Node JS server using a server-client architecture.
# Tailwind CSS Styling: 
Enjoy a visually appealing and customizable design with Tailwind CSS, following the guidelines provided in the Tailwind CSS documentation.

## Dependencies

### Server Dependencies
- Express
- Body-parser
- Cors
- Dotenv
- Node-fetch
#### do : npm i express body-parser cors dotenv node-fetch

### Server Command Dependencies
- Nodemon (for development)
#### do : npm install -D nodemon

### To run the server : npm run dev
![server run dev](https://github.com/fenil210/Chat-GPT-Clone/assets/121050723/cf6f463e-f61e-468c-b335-f60eeacb9b8b)


### Client Dependencies
- React
- React-dom
#### do : npm i react react-dom

### To run the client : npm run dev
![client run dev](https://github.com/fenil210/Chat-GPT-Clone/assets/121050723/0b380555-6734-435c-a6ba-bab9915648f2)


### Tailwind CSS
To set up Tailwind CSS in the client folder, follow the instructions in [Tailwind CSS Documentation](https://tailwindcss.com/docs/guides/vite).

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository: `git clone github.com/fenil210/Chat-GPT-Clone`
2. Navigate to the project folder: `cd server` and 'cd client'

## Configuration

Ensure you have the necessary API keys and configurations set up. You may need to create a `.env` file in the root directory with the required environment variables.

Example `.env` file:
```env
OPENAI_API_KEY=paste_your_openai_api_key_here
