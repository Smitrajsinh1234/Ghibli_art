# Text_to_Ghibli_art
Geerative ai that creates authentic japanese ghibli art style images.
# Text-to-Ghibli Image Generation Model 🎨✨

A fine-tuned AI model that generates **Ghibli-style images** from text prompts. Just type what kind of image you want, and the model will create it in the iconic **Ghibli art style**.

---

## Features
- Converts **text prompts** into high-quality Ghibli-style images.
- Fine-tuned on **open-source Ghibli art-style images**.
- Produces **detailed, vivid, and visually appealing outputs**.
- Easy to integrate into Python projects or AI pipelines.

---

## Demo
You can try the model here:  
[GitHub Repository](https://github.com/yourusername/Text-to-Ghibli-Model)  
*(Replace with your repo link after uploading)*

---

## Dataset
- Used **open-source Ghibli art-style images** for training.
- Focused on capturing **unique colors, textures, and styles** characteristic of Studio Ghibli.

---

## Model Details
- **Type:** Fine-tuned Text-to-Image Model  
- **Training Technique:** LoRA fine-tuning  
- **Number of Images:** 2000+ captioned images  
- **Framework:** PyTorch / Hugging Face Diffusers

---

## Usage
```python
from transformers import pipeline

# Load the model (replace with your model path or repo)
generator = pipeline("text-to-image", model="yourusername/Text-to-Ghibli-Model")

# Generate an image
prompt = "A cozy cottage in a magical forest, Ghibli style"
image = generator(prompt)[0]
image.save("output.png")
