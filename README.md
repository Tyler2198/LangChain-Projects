# 🚀 LLM-Powered Financial Analysis Tool

## 📌 Overview
This project demonstrates how to build a **simple but powerful financial analysis tool** using **Large Language Models (LLMs)**. By leveraging **LangChain**, we generate insights about different stocks based on structured prompts. 

### 🎯 Key Features:
- Uses **LLMs for financial stock analysis**.
- Implements **chat models and prompt templates**.
- Supports **dynamic stock selection** for analysis.
- Works with **Groq's Llama 3 model**.

## 🔧 Installation
To run this project locally, follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/LLM-Finance-Analysis.git
cd LLM-Finance-Analysis
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set API Keys
This project uses **Groq API** for LLM inference. Set your API key:
```python
import os
os.environ["GROQ_API_KEY"] = "your_api_key_here"
```

Alternatively, store it securely in a `.env` file:
```plaintext
GROQ_API_KEY=your_api_key_here
```
Then load it in Python:
```python
from dotenv import load_dotenv
load_dotenv()
```

## 📊 Usage
### Run the Notebook:
Launch Jupyter Notebook:
```bash
jupyter notebook
```
Open **`A simple LLM application for finance.ipynb`**, and execute the cells step by step.

### 🔍 Example Analysis
The notebook allows users to:
- Set a **system message** with the stock name.
- Define a **standardized prompt** for any stock.
- Get an **LLM-generated financial summary**.

For example:
```python
stock = "ASML"
prompt = f"Analyze the financial health of {stock} based on recent trends and key metrics."
```
🚀 **Output:**
*"ASML has demonstrated strong financial performance with robust revenue growth and increasing investments in semiconductor technology..."*

## 📈 Future Enhancements
✅ Support for **multiple LLM providers** (OpenAI, Mistral, Claude).  
✅ Implement **retrieval-augmented generation (RAG)** for better financial insights.  
✅ Add **data visualization** for key stock metrics.  

## 🛠️ Technologies Used
- 🧠 **LangChain** – LLM orchestration  
- 🤖 **Groq API** – Llama 3 model  
- 🐍 **Python** – Core programming  
- 📊 **Jupyter Notebook** – Interactive execution  

## 🌍 Contributions
Want to improve this project? **Feel free to fork and contribute!**  
Simply:
1. **Fork** this repo
2. **Create a feature branch** (`git checkout -b feature-xyz`)
3. **Commit changes** (`git commit -m "Added new feature"`)
4. **Push and create a pull request!** 🚀  
