# Generative-AI-Experiments-with-Gemini-AIs

## Setup Instructions
#### 1. Clone the repository
First, clone this repository to your local machine:
```
git clone https://github.com/Sithum-Bimsara/LangChain-Chatbot-with-OpenAI-and-Ollama-LLMs.git
cd LangChain-Chatbot-with-OpenAI-and-Ollama-LLMs
```
#### 2. Create a Virtual Environment
If you haven't already created a virtual environment (venv), follow these steps to set it up:

On Windows:
```
python -m venv venv
```
On macOS/Linux:
```
python3 -m venv venv
```
#### 3. Activate the Virtual Environment
On Windows:
```
.\venv\Scripts\activate
```
On macOS/Linux:
```
source venv/bin/activate
```
#### 4. Install Dependencies
Once the virtual environment is activated, install the required dependencies from requirements.txt:
```
pip install -r requirements.txt
```
#### 5. Set Up Environment Variables
Create a `.env` file in the root directory (if it doesn't exist) and add the following environment variables for your API keys:
```
GOOGLE_API_KEY="your_google_api_key"
```

#### 6. Run the Application

To run the GEMINI-AI-powered applcations y:
```
streamlit run app(replace this with the file name).py
```
Once the app is running, it will be accessible in your browser at http://localhost:8501.

#### 7. Stopping the App
To stop the application, simply press `Ctrl+C` in the terminal where the app is running.

## Requirements
The dependencies for this project are listed in requirements.txt. You can view the contents of requirements.txt below:
```
streamlit
google-generativeai
python-dotenv
PyPDF2
faiss-cpu
langchain
langchain-community
langchain_google_genai
langchain-text-splitters
pdf2image
youtube_transcript_api
```
## Troubleshooting
Ensure that your .env file contains valid API keys and there are no syntax issues. If you encounter errors related to missing packages, try running pip install -r requirements.txt again. Make sure you're using a Python version of 3.7 or higher. 

## Contributing
Feel free to fork this repository and submit pull requests if you'd like to contribute to the project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
