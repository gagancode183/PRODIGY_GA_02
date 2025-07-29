
# 🖼️ Text-to-Image Generation with Stable Diffusion (Colab)

This notebook enables **text-to-image generation** using the powerful **Stable Diffusion v1.5** model via Hugging Face's 🤗 `diffusers` library.  
Runs seamlessly on **Google Colab** — no setup or GPU required locally.

---

## 🚀 Features

- 🎨 Generates **high-quality images** from **natural language prompts**.
- ⚡ Uses **Stable Diffusion v1.5** from `runwayml`.
- 🖥️ **GPU acceleration** in Colab (if available).
- 💾 Saves generated images locally as `.png`.
- 👁️ Displays image directly in the notebook.

---

## 📋 Requirements

If you're using **Google Colab**, you're all set ✅.  
Otherwise, install the required libraries manually:

```bash
pip install diffusers transformers accelerate safetensors
```

---

## 🧪 How to Use

1. **Open the notebook in Google Colab**  
   👉 [Click here to open in Colab](#) *(Replace with actual link if publishing)*

2. **Install dependencies**  
   Run the first cell to install required libraries.

3. **Edit the prompt**  
   Modify the `prompt` string to your desired description:

   ```python
   prompt = "A futuristic cityscape at night with neon lights, cyberpunk style"
   ```

4. **Run the notebook**  
   Execute all cells. Image generation will take ~20 seconds.

5. **View the result**  
   - Image will be displayed inline.
   - Saved as `generated_image.png`.

---

## 🧠 Model Details

- **Model**: [`runwayml/stable-diffusion-v1-5`](https://huggingface.co/runwayml/stable-diffusion-v1-5)
- **Architecture**: Latent Diffusion Model (LDM) by **CompVis**
- **Source**: Hugging Face 🤗 `diffusers`

---

## 📁 Output

- ✅ **Display**: Output image shown in notebook.
- ✅ **Storage**: Automatically saved as `generated_image.png`.

---

## 📌 Sample Output

![Sample](generated_image.png)  
*Prompt: "A futuristic cityscape at night with neon lights, cyberpunk style"*

---

## 💬 License & Credits

- Model by [CompVis](https://github.com/CompVis), distributed via [Hugging Face](https://huggingface.co).
- Based on the [Stable Diffusion](https://stability.ai/blog/stable-diffusion-announcement) architecture.
