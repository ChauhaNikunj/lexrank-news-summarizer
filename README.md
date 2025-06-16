# 🧠 LexRank News Summarizer
This project implements an AI-powered summarization tool using the **LexRank** algorithm to condense long-form news articles into concise, informative summaries. It is designed for performance, clarity, and compatibility with Kaggle notebooks and low-resource machines.

Link to the [Kaggle Notebook](https://www.kaggle.com/code/billubodmas/ai-new-sumarrizer-using-lexrank)
---

## 📚 Dataset

- **Source**: [Global News Dataset on Kaggle](https://www.kaggle.com/datasets/everydaycodings/global-news-dataset)
- Includes structured metadata and full-text news articles.

---

## 💡 Features

- Preprocessing of large-scale text data
- Extractive summarization using LexRank via `sumy`
- Visual comparison between full content and generated summaries
- Compression ratio analysis

---

## 📊 Visual Outputs

- **Summary vs. Full Article Length** (Line graph)
- **Text Compression Ratios** between original and summarized content

---

## 🛠️ Tools & Technologies

- **Python**, Kaggle Notebook  
- **`pandas`** — *for efficient data manipulation and analysis*  
- **`sumy`** — *for extractive summarization using the LexRank algorithm*  
- **`matplotlib`** — *for creating visualizations and comparative plots*  
- Optional: **`nltk`** — *for tokenizer support*
