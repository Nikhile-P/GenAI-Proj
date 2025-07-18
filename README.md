🤖 Next Sentence Predictor
![Hugging Face](https://www.google.com/search?q=https://img.shields.io/badge/%25F0%259F%25A4% hugging%20face-Transformers-yellow)

A high-performance web application for real-time, controllable text generation using a pre-trained GPT-2 model. This project demonstrates the implementation of a generative AI system from ideation to a fully functional and tested application.

► Live Demo & Preview
[Link to your deployed Streamlit App]

(Note: To create a GIF, you can use a free tool like Giphy Capture or ScreenToGif, record your app in action, and upload the GIF file to this repository.)

Project Overview
This project is a practical implementation of a generative AI system designed for real-world text completion tasks. It leverages the Hugging Face Transformers library to serve a pre-trained GPT-2 model through a clean and responsive user interface built with Streamlit. The application demonstrates efficient model serving, interactive parameter tuning, and the ability to generate coherent, context-aware text sequences.

Core Functionalities
Dynamic Text Generation: Produces multiple, unique sentence completions from a user-provided prompt.

User-Controlled Parameters: Allows for real-time adjustment of key generation parameters, including maximum length and top-k sampling for creativity control.

Optimized Model Caching: Utilizes Streamlit's @st.cache_resource to load the model into memory once, ensuring minimal latency on subsequent prediction requests.

Modern UI/UX: A polished, two-column interface designed for intuitive interaction and clear presentation of results.

System Architecture & Tech Stack
The application is built on a stack designed for rapid development and deployment of machine learning applications:

Frontend: Streamlit is used for creating the interactive web interface.

Backend & Machine Learning:

Python serves as the backend language.

Hugging Face Transformers provides the core functionality for accessing and utilizing the pre-trained GPT-2 model.

PyTorch runs as the backend tensor library for the model.

Application Code
Click to view the full application code (app.py)
Local Setup and Execution
Prerequisites
Python 3.8+

pip package manager

Git

Installation
Clone the Repository

Bash

git clone https://github.com/Nikhile-P/GenAI-Proj.git
cd GenAI-Proj
Install Dependencies

Bash

pip install -r requirements.txt
Launching the Application
Execute the following command to run the Streamlit server:

Bash

streamlit run app.py
The application will be accessible at http://localhost:8501.

Project Documentation
Project Execution Summary
Testing Strategy
Development Roadmap
Potential enhancements for future versions include:

Model Fine-Tuning: Fine-tuning the GPT-2 model on a domain-specific corpus to generate more accurate and context-aware sentences.

User Feedback Loop: Incorporating a feedback mechanism to allow the model to adapt and improve from user ratings.

Multi-Language Support: Extending the model's capabilities to support multiple languages.

API Exposure: Encapsulating the prediction logic within a REST API to allow for integration with other services.

License
This project is licensed under the MIT License.
