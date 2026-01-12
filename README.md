# Fine-tuning Phi-2 for Abstractive Text Summarization (XSum)

Repository ini berisi implementasi **fine-tuning model Phi-2 (decoder-only LLM)** untuk tugas **abstractive text summarization** menggunakan dataset **XSum** dari HuggingFace Datasets.  
Proyek ini dibuat sebagai bagian dari **UAS (Final Term) mata kuliah Deep Learning**.

---

## 🎯 Tujuan

Membangun sistem summarization end-to-end berbasis Transformer dengan:
- Preprocessing dataset XSum  
- Fine-tuning model Phi-2  
- Evaluasi performa menggunakan metrik ROUGE  
- Analisis hasil prediksi dan error model  

---

## 📌 Ringkasan Proyek

| Komponen | Detail |
|--------|------|
| Dataset | xsum |
| Model | Phi-2 |
| Arsitektur | Decoder-only (LLM) |
| Tugas NLP | Abstractive Text Summarization |
| Metrik utama | ROUGE-1, ROUGE-2, ROUGE-L |
| Metrik opsional | ROUGE-Lsum |

---

## 🗂 Struktur Folder

| Folder | Deskripsi |
|------|----------|
| `notebooks/` | Notebook eksperimen (preprocess → training → evaluasi) |
| `reports/` | Tabel metrik, grafik, dan analisis kualitatif |
| `requirements.txt` | Daftar dependensi |

---

## ▶️ Cara Menjalankan

1. Buat virtual environment (conda / venv)
2. Install dependensi:

```bash
pip install -r requirements.txt
