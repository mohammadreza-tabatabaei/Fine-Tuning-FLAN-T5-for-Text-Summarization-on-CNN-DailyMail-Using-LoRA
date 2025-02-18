# Fine-Tuning FLAN-T5 for Text Summarization on CNN/DailyMail Using LoRA

This project fine-tunes Google's **FLAN-T5** model for text summarization using the **CNN/DailyMail** dataset. The model is optimized using **LoRA (Low-Rank Adaptation)** to reduce the number of trainable parameters while maintaining performance.

## 📌 Features
- Fine-tunes **FLAN-T5-small** for abstractive text summarization.
- Uses **LoRA** to modify dense layers and make training more efficient.
- Preprocesses data from **CNN/DailyMail** and tokenizes using `transformers` library.
- Evaluates the model using **BLEU Score**.

## 📂 Dataset
We use the **CNN/DailyMail (version 3.0.0)** dataset, which consists of news articles and their corresponding summaries.

## 📊 Results
After training for **3 epochs**, I got an average **BLEU score**.

## 📌 Future Improvements
- Use larger versions of **FLAN-T5** for better summaries.  
- Implement **ROUGE Score** for additional evaluation metrics.  
- Fine-tune on other summarization datasets like **XSum**.  

## 📜 License
This project is open-source and licensed under the **MIT License**.
