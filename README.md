# 🧾 Invoice Extractor using SmolVLM 

Extract structured fields like invoice number, date, total amount, and line items from scanned invoices using HuggingFace’s `SmolVLM-Instruct` model or `Idefics3` multimodal vision-language model — all within a **Kaggle Notebook** environment.

<p align="center">
  <img src="examples/sample_invoice.jpg" width="600"><br>
  <em>Visual Invoice Understanding in Action</em>
</p>

---

## 📍 Hosted on Kaggle

▶️ Run the full notebook here:  
🔗 **[View on Kaggle](https://www.kaggle.com/code/aryanmudgal03/invoice-extractor)**

---

## 🔍 Features

- 🖼️ Vision-language model for document understanding
- 🧾 Prompt-based extraction (zero-shot)
- ✅ Works entirely on **Kaggle**, no setup required
- 📦 Upload your own invoice images (JPEG/PNG)
- 🧠 Uses open-source `SmolVLM-Instruct` from Hugging Face

---

## 📁 How to Use (Kaggle)

1. Go to the Kaggle Notebook → [Invoice Extractor](https://www.kaggle.com/code/aryanmudgal03/invoice-extractor)
2. Upload your invoice image(s) in the `data/` or `/kaggle/input` folder
3. Modify the prompt to match your data format
4. Run all cells to extract structured data from image

---

## 🧠 Model 

Model: [`HuggingFaceTB/SmolVLM-Instruct`](https://huggingface.co/HuggingFaceTB/SmolVLM-Instruct)


