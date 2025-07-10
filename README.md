## Text-to-Image Generator

## ✨ Overview

This project is a web-based AI image generator built with **Stable Diffusion XL (SDXL)**.  
It transforms any text prompt into realistic, high-quality images using the power of **diffusion models**, all inside **Google Colab** with GPU acceleration.

## 🚀 Features

- 🖼️ Generate AI images from any prompt
- ⚡ Runs on free **Google Colab T4 GPU**
- 🧠 Powered by **Hugging Face Diffusers & PyTorch**
- 🌐 Clean, instant Gradio web interface
- ⏱️ Shows generation time for each image
- ✅ No API key or Hugging Face token required


## 🧪 How It Works

1. **Open notebook in Google Colab**
2. Switch to **T4 GPU**:  
   `Runtime → Change runtime type → Hardware accelerator → GPU`
3. Run all cells  
4. Click on the **Gradio link** generated in output  
5. Enter a prompt → get an image → download if you like


## 🧠 Tech Stack

| Tool         | Purpose                          |
|--------------|----------------------------------|
| `diffusers`  | Load & run the SDXL model        |
| `torch`      | GPU-accelerated computation      |
| `gradio`     | Web interface for interaction    |
| `PIL`        | Image saving and manipulation    |


## 📝 License

This project uses open-source tools and is free for educational and personal use.


> Built with ❤️ by Ashish Saini using open-source AI
