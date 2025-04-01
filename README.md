# Ai-powered-Job-assistant-chatbot
# AI-Powered Job Assistant Chatbot

This repository contains an AI-powered job assistant chatbot that leverages Retrieval-Augmented Generation (RAG) and the FAISS algorithm for vector space search. It uses Streamlit for the frontend, the GROQ API for productivity, LangChain for LLM processing, and Jooble API for job listings.

## Features
- **AI-driven job recommendations** based on user preferences
- **Retrieval-Augmented Generation (RAG)** for enhanced responses
- **FAISS-based vector search** for efficient query handling
- **Integration with OpenAI, GROQ, and Jooble APIs**
- **User-friendly Streamlit frontend**

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/jai2509/Ai-powered-Job-assistant-chatbot.git
cd Ai-powered-Job-assistant-chatbot
```

### 2. Set Up a Virtual Environment
It is recommended to create a virtual environment to manage dependencies.

```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
Ensure you have `pip` installed and then install the required packages:
```bash
pip install -r requirements.txt
```

### 4. Configure API Keys
Create a `.env` file in the project root directory and add the following keys:
```ini
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
JOOBLE_API_KEY=your_jooble_api_key
```
Replace `your_openai_api_key`, `your_groq_api_key`, and `your_jooble_api_key` with your actual API keys.

### 5. Run the Application
Start the chatbot using Streamlit:
```bash
streamlit run app.py
```

## Usage
- Open the application in your browser (usually at `http://localhost:8501`)
- Enter your job-related queries
- The chatbot provides AI-based job recommendations and career guidance

## Requirements
All dependencies are listed in `requirements.txt`. Here are some key dependencies:
```txt
streamlit
langchain
faiss-cpu
groq-api
openai
python-dotenv
requests
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contact
For any queries or issues, please open an issue in the repository or contact the maintainer.

---
### Happy Coding! 🚀
