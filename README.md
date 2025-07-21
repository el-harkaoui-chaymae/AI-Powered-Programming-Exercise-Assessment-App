# AI-Powered-Programming-Exercise-Assessment-App

🔴 This project focuses on the development of an AI-powered chatbot system designed to automatically evaluate programming assignments submitted by students. The system mimics the role of a programming instructor analyzing student code, identifying errors, suggesting corrections, assigning a score, and providing an explanation to justify the score. 

🔴 The primary goals of this project are: 

**1 - Automatically Evaluate Code Correctness** 
Analyze submitted code to determine whether it correctly solves the given problem, 
identifying both syntactic and semantic issues. 

**2 - Detect and Explain Mistakes** 
Provide clear, concise explanations of any errors or suboptimal implementations found in the 
submitted code, helping users understand what went wrong and why. 

**3 - Suggest Improved or Corrected Solutions** 
Generate corrected versions of the submitted code or suggest better alternatives that align 
with best practices and solve the task as intended.


🔴 Technologies Used :

**1 - Python**
Python is a powerful, high-level programming language known for its simplicity and readability. It is widely used in web development, data analysis, artificial intelligence, and automation. In this project,Python is the backbone of the backend system, primarily used with the Flask framework and LangChain library to create logic for handling user inputs, integrating with the language model, and processing code evaluations. Python's ecosystem of libraries and its ease of integration with AI tools made it the ideal choice for implementing the server-side logic of this chatbot. 

**2 - LangChain** 
LangChain is a framework that simplifies the development of applications powered by large language models (LLMs). It provides modular components to structure prompts, manage memory, chain responses, and integrate with external tools. In this project, LangChain is used to define prompt templates and chain interactions between the exercise input, student code, and the local LLM. It abstracts the complexity of communicating with the language model, making the evaluation logic cleaner, reusable, and easier to manage. 

**3 - Ollama** 
Ollama is a local runtime platform for deploying and interacting with large language models (LLMs) offline. It enables developers to run advanced models like CodeLLaMA, DeepSeekCoder, and Mistral on their machines without needing cloud infrastructure or internet connectivity. In this project, Ollama powers the core AI engine responsible for analyzing and scoring student code. Its local-first approach ensures privacy, speed, and complete control over the AI evaluation process. 

**4 - React** 
React is a JavaScript library developed by Facebook for building fast, dynamic, and interactive user interfaces. It follows a component-based architecture, allowing developers to build reusable UI components. In this project, React is used to create the frontend interface where users can input programming problems and student code. It also renders the evaluation results received from the backend, ensuring a responsive and user-friendly experience across different devices. 

**5 - Flask** 
Flask is a lightweight web framework for Python, known for its flexibility and minimalistic design. It provides essential tools and features to build web APIs and applications quickly. In this project, Flask
serves as the backend API that receives data from the React frontend, processes it using LangChain and the LLM through Ollama, and returns the evaluation output. Flask’s simplicity made it easy to set up routing, handle HTTP requests, and integrate with the rest of the AI stack 
