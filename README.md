---
title: Langchain Llama2 Chatbot
emoji: 🌍
colorFrom: blue
colorTo: green
sdk: streamlit
sdk_version: 1.32.2
app_file: app.py
pinned: false
license: mit
---

In this project, we developed a chatbot using llama2.

To run this project locally, you need to create a clone of this project

Then run:
```
conda create -p venv python==3.10 -y
conda activate
pip install -r requirements.txt
```

Also make sure that you have `ollama` downloaded on your system, if not, download it from [here](https://ollama.com/download)

Run:
```
ollama run llama2
```

Now you are good to go, simply run:
```
streamlit run app.py
```


Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
