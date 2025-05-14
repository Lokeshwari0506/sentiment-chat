# 🤖 Multiclass Sentiment-Aware Chatbot (with Gradio UI)

This project is an **open-source sentiment-aware chatbot** built using **Hugging Face Transformers**, **Gradio**, and **Google Colab**. It classifies user input into fine-grained emotions such as *happy, sad, angry, fear, surprise,* and *love*, then generates a human-like response based on the context and sentiment.

## 🌐 Demo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oakGhJ21K4JbwLtj_Je-L8gb5shsTtj4#scrollTo=bIjS9MErU1zv)

## ✨ Features

- 🎯 **Multiclass Sentiment Detection**: Classifies input into emotions beyond just positive/negative/neutral.
- 🔁 **Contextual Reply Generator**: Generates empathetic chatbot replies using BlenderBot.
- 📊 **Confidence Scores**: Shows how confident the model is in each emotion class.
- 🖼️ **Gradio UI**: Easy-to-use web interface for interacting with the chatbot.

## 📦 Models Used

| Task                    | Model                                                  |
|-------------------------|--------------------------------------------------------|
| Sentiment Classification | `bhadresh-savani/distilbert-base-uncased-emotion`      |
| Reply Generation         | `facebook/blenderbot-400M-distill`                    |

All models are open-source and served using [🤗 Hugging Face Transformers](https://huggingface.co/models).

## 🛠️ Setup Instructions

### 1. Open in Google Colab

Click the "Open in Colab" badge above to launch the notebook in Google Colab.

### 2. Run the Notebook

Click **Runtime → Run all** to install dependencies and start the chatbot.

### 3. Launch UI

Once all cells run, Gradio will show a link. Click it to open the chatbot UI.

## 📁 File Structure

#### chatbot_emotion_colab.ipynb # Main Colab notebook
#### README.md # This file


## 💡 To-Do

- [ ] Add memory for multiple turns
- [ ] Integrate with a backend API (Flask/FastAPI)
- [ ] Save chat logs and responses

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute, feel free to fork the repo and submit improvements.


---

Made with ❤️ using open-source tools.
