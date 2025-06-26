# Fine-tuning XLS-R for Multilingual ASR using FLEURS

This project focuses on fine-tuning the [XLS-R 300M model](https://huggingface.co/facebook/wav2vec2-xls-r-300m) for automatic speech recognition (ASR) in a low-resource African language using the [FLEURS dataset](https://huggingface.co/datasets/google/fleurs). It leverages Hugging Face's `transformers`, `datasets`, and `torchaudio` libraries for a robust multilingual ASR pipeline.

---

## 🎯 Objectives

- Preprocess and normalize the FLEURS audio dataset for ASR.
- Train a Wav2Vec2-based CTC model (XLS-R) on low-resource language data.
- Evaluate transcription performance using WER and CER.
- Upload the trained model and tokenizer to the Hugging Face Hub.

---

## 🧰 Tools & Libraries

- `transformers`
- `datasets`
- `torchaudio`
- `jiwer`
- `wandb` (for experiment tracking)
- `accelerate`, `librosa`, `git-lfs`, `huggingface_hub`

---

