
# 🎨 PromptCraft: Fine-Tuning & Evaluating Stable Diffusion

This project demonstrates fine-tuning and evaluating a Stable Diffusion model using custom datasets. It includes training using LoRA or full fine-tuning methods, and evaluation using CLIP Similarity and Inception Score metrics.

## 📁 Notebooks

### 🧪 Lab2_Part2_Finetune_SD.ipynb
- Installs and prepares required packages (Diffusers, Transformers, PEFT)
- Fine-tunes a Stable Diffusion model (e.g., SD 1.5 or SDXL) using a custom dataset
- Supports methods like LoRA and QLoRA for efficient training
- Saves the fine-tuned model for inference

### 📈 Lab2_Part2_SD_Evaluation.ipynb
- Loads the fine-tuned model
- Generates images based on different prompts
- Computes evaluation metrics:
  - 📊 Inception Score (IS)
  - 🧠 CLIP Similarity Score

## 🔧 Setup Instructions

### 🐍 Install Dependencies

```bash
pip install diffusers transformers accelerate datasets pillow peft torch torchvision tqdm ipywidgets
```

---

## 🏁 How to Run

1. Prepare your dataset (art, landscapes, anime, etc.)
2. Run `Lab2_Part2_Finetune_SD.ipynb` to fine-tune the model
3. Run `Lab2_Part2_SD_Evaluation.ipynb` with at least 5 prompts to generate and evaluate images

---

## 📊 Evaluation Metrics

- **Inception Score (IS)**: Measures image diversity and quality
- **CLIP Similarity**: Evaluates how well images align with prompts

---

## 📌 License

This project is for research and educational purposes only.
