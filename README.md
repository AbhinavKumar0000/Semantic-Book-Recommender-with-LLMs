Semantic Book Recommender with LLMs
This project is a Semantic Book Recommender that leverages the power of Large Language Models (LLMs) to provide highly accurate and context aware book recommendations. Unlike traditional collaborative filtering or content-based systems, this application understands the meaning and nuance of your query to find books that are semantically similar to your preferences.

Features
Semantic Search: Finds books based on the meaning of your query, not just keywords.

LLM-Powered Recommendations: Utilizes a powerful LLM to analyze book descriptions and user input for deep understanding.

Natural Language Queries: Allows users to ask for recommendations using everyday language, such as "books about a detective solving a mystery in 1920s London."

Fast & Efficient: Uses a vector database (FAISS) for quick and scalable similarity searches.

User-Friendly Interface: The application is built with a simple and intuitive interface for a smooth user experience.

🛠️ Technologies Used
Python: The core programming language for the project.

LLMs: Used for generating embeddings and understanding semantic context.

Sentence-Transformers: A Python framework for state of the art sentence, text, and image embeddings.

FAISS: A library for efficient similarity search and clustering of dense vectors.

Streamlit: A framework to build a simple and interactive web application for the recommender.

⚙️ Installation
To get a local copy up and running, follow these simple steps.

Clone the repository:

git clone https://github.com/AbhinavKumar0000/Semantic-Book-Recommender-with-LLMs.git
cd Semantic-Book-Recommender-with-LLMs

Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install the required dependencies:

pip install -r requirements.txt

Usage
To start the application, navigate to the project directory and run the Streamlit app:

streamlit run app.py

The application will open in your web browser. You can then enter a natural language query in the text box and get book recommendations based on the semantic meaning of your input.

Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request



📧 Contact
Abhinav Kumar - abhinavkumarsaksena@gmail.com

Project Link: https://github.com/AbhinavKumar0000/Semantic-Book-Recommender-with-LLMs
