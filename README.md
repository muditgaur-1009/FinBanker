
# FinBanker: Your Personal Finance Q&A Chatbot

Welcome to FinBanker, an AI-powered Q&A chatbot designed to provide instant answers to your financial queries. FinBanker combines the power of Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) techniques to deliver accurate and contextually relevant responses.

## 🌟 Features
- **Comprehensive FAQ Coverage:** Trained on a wide range of frequently asked financial questions.
- **Intelligent Query Handling:** Utilizes LLMs for understanding natural language queries and generating responses.
- **Contextual Relevance:** Employs RAG techniques to retrieve and incorporate information from a knowledge base, ensuring accurate and contextually relevant answers.
- **User-Friendly Interaction:** Enjoy a seamless chat experience designed for ease of use.

## 🚀 Getting Started
### Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.7 or higher
- Jupyter Notebook
- Hugging Face API Token

### Installation
Clone the repository:
```bash
git clone https://github.com/your-username/FinBanker.git
cd FinBanker
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
Set up your Hugging Face API token:
```python
import os
os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_huggingface_api_token"
```

### Running the Chatbot
Open the Jupyter Notebook:
```bash
jupyter notebook genai-finance-chatbot.ipynb
```
Run the notebook cells to initialize the chatbot.

Start interacting with FinBanker:
```bash
Welcome to FinBanker, your personal finance Q&A assistant. How can I assist you today?
You: How can I obtain an IVR Password?
FinBanker: By Sending SMS request: Send an SMS 'PWD<space>Last Four Digits of Credit Card Number' to the given number.
```

## 📂 File Structure
- **genai-finance-chatbot.ipynb:** The main Jupyter Notebook containing the Q&A chatbot implementation.
- **requirements.txt:** A file listing the dependencies required to run the chatbot.

## 🌐 Usage
Start a conversation with FinBanker and ask any financial question you have. Here's an example interaction:
```vbnet
You: What details are required when I want to perform a secure IVR transaction?
FinBanker: To perform a secure IVR transaction, you will need your card number, expiry date, and CVV number.
```

## 🤝 Contributing
We welcome contributions to enhance FinBanker! Here’s how you can help:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 💡 Acknowledgments
Special thanks to the Hugging Face community and all the contributors who made this project possible.

Start chatting with FinBanker today and get instant answers to your financial questions! 🏦

