# 🦥 Llama 2 AI Chatbot

Llama 2 AI Chatbot is a conversational AI powered by Meta's Llama 2 model, integrated with LangChain and Streamlit. This chatbot allows users to interact with the model in real time via a web interface.

## 🚀 Features
- Uses **Llama 2 (7B)** model for natural language processing.
- Integrated with **LangChain** for seamless prompt engineering.
- **Streamlit** web UI for user-friendly interaction.
- Deployed using **ngrok** for external access.

## 📛 Installation
### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/llama2-chatbot.git
cd llama2-chatbot
```

### Step 2: Install Dependencies
```bash
pip install langchain openai llama-cpp-python streamlit streamlit_chat langchain_community pyngrok
```

### Step 3: Download Llama 2 Model
Download the **Llama 2 7B GGUF** model file:
```bash
wget -O llama-2-7b.gguf https://huggingface.co/TheBloke/Llama-2-7B-GGUF/resolve/main/llama-2-7b.Q4_K_M.gguf
```

## 🛠️ Usage
### Run the Chatbot
```bash
streamlit run app.py
```

### Deploy with ngrok
1. Authenticate ngrok (replace with your token):
   ```bash
   ngrok authtoken YOUR_NGROK_AUTH_TOKEN
   ```
2. Start ngrok tunnel:
   ```bash
   ngrok http 8501
   ```
3. Copy the **public URL** provided by ngrok and open it in a browser.


