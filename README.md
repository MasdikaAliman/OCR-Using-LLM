# Vehicle License Plate OCR using Vision-Language Model (VLM)

This project performs Optical Character Recognition (OCR) on Indonesian vehicle license plates using a Vision-Language Model (VLM) via [LM Studio](https://lmstudio.ai/). The system processes plate images, queries the model for transcription, and evaluates accuracy using Character Error Rate (CER).

---

## 📌 Features

- 🔍 Performs OCR on vehicle license plates using VLM
- 🤖 Integrates with LM Studio via API calls
- 📊 Evaluates performance using CER (Character Error Rate)
- 🖼️ Supports batch processing of images in a directory

---

## 🧰 Requirements

- Python 3.8+
- Jupyter Notebook
- Required packages:
  - `Levenshtein`
  - `pandas`
  - `lmstudio`
  - `os`
  - `icecream-python`

Install required packages:
```bash
pip install requests pillow matplotlib scikit-learn
