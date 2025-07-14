# 🖼️ Stable Diffusion Image Generator (Streamlit + Colab + LocalTunnel)

This project allows you to generate AI images using [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4), wrapped in a simple **Streamlit UI**, and hosted directly from **Google Colab** with public access via **LocalTunnel**.

> ✅ No `ngrok` authtoken or server setup required.

---

## 📌 Features

- Text-to-image generation using Hugging Face's Stable Diffusion
- Streamlit-based interactive UI
- 100% works from Google Colab
- No need for ngrok token (uses LocalTunnel instead)

---

## 🛠️ Setup (in Google Colab)

### 🔗 Open in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/app.ipynb)

---

## 🧪 How to Run

1. **Run each cell one by one.**

2. The notebook will:
    - Install dependencies (`diffusers`, `transformers`, `Streamlit`, `LocalTunnel`)
    - Download the Stable Diffusion model
    - Launch a Streamlit app
    - Expose it using LocalTunnel

3. ✅ After a few seconds, you'll see a **public URL** in the output like:
"your url is: https://fancy-name.loca.lt"