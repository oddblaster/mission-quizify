# Mission Quizify
Mission Quizify is an innovative application that enables users to test their knowledge on any subject matter. Leveraging the power of Google Cloud, Vertex AI, Langchain, and Streamlit, this application utilizes artificial intelligence to transform information from uploaded documents into questions, answer choices, and explanations.

# Features:
Document Parsing: Upload a PDF containing readable notes and information. The application uses ChromaDB to parse the document into different embeddings for further processing by Gemini.
Question Generation: Utilizing artificial intelligence, the application generates questions based on the content of the uploaded document.
Answer Choices and Explanations: Along with each question, the application provides multiple answer choices and explanations to aid in understanding.

# How to Install:
## 1. Install Google Cloud:
Ensure you have Google Cloud installed and configured properly.

## 2. Setup Service Account:
Set up a service account with the necessary permissions to access Google Cloud services. Download the json file and rename it.

## 3. Clone Repository:
Clone this repository to your local machine. Make sure to move the the json file to your file location in which you are working on the repository.

## 4. Environment Setup:
Python Version: Ensure you have Python 3.10.8 installed.
Install pip: Ensure you have pip 22.2.2 installed.
## 5. Virtual Environment:
Create a virtual environment:

python -m venv env

### Activate the virtual environment:

#### For Windows:
env\Scripts\activate

#### For Unix or MacOS:
source env/bin/activate

## 6. Install Dependencies:
Install the required dependencies using the following command:

pip install -r requirements.txt
## 7. Authenticate Service Account:
Authenticate the service account within the virtual environment by setting the GOOGLE_APPLICATION_CREDENTIALS environment variable:

## set GOOGLE_APPLICATION_CREDENTIALS=service_account_key.json

# Questions or Support:
If you have any questions or need support, feel free to contact me at chuyangzhanggeorge@gmail.com

Thank you for the contribution and educational support from RadicalAI
