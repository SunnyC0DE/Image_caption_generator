# 🖼️ Image Caption Generator (Hugging Face Transformers)

This project uses a pre-trained Vision-to-Text model from Hugging Face (`vit-gpt2`) to automatically generate descriptive captions for input images.

---

## 📌 Description

 Built an advanced image captioning system using the BLIP
 (Bootstrapped Language-Image Pretraining) transformer model from
 Hugging Face. The system generates human-like captions from input
 images by combining vision transformers with natural language
 generation.
This project demonstrates a modern and production-ready image captioning pipeline using Hugging Face Transformers and PyTorch.

---

## 🧠 Features

- Accepts user images and generates captions
- Uses a state-of-the-art ViT-GPT2 model from Hugging Face
- Accepts drag-and-drop images (if UI enabled via Streamlit or Gradio)
- Clean, modular code — easy to extend or fine-tune

---

## 🔧 Technologies Used

- Python 3
- Hugging Face Transformers
- PyTorch
- PIL (Python Imaging Library)
- Optional: Streamlit or Gradio (for web UI)

---

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/SunnyC0DE/image_caption_generator.git
cd image_caption_generator

# Install dependencies
pip install -r requirements.txt

# Run the script (CLI or Streamlit)
python app.py
