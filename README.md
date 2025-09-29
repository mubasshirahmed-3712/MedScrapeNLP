# MedScrapeNLP 🧬  
*From Raw XML to Clean Insights: Unlocking Medical Text with NLP*  

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)  
![NLP](https://img.shields.io/badge/NLP-NLTK-green?logo=natural-language-processing)  
![BeautifulSoup](https://img.shields.io/badge/WebScraping-BeautifulSoup-yellow?logo=beautifulsoup)  
![License](https://img.shields.io/badge/License-MIT-lightgrey)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview  
**MedScrapeNLP** is an **end-to-end NLP pipeline** for parsing **medical research articles in XML format**.  
It extracts metadata (title, author, keywords, publication date) and body text, cleans and preprocesses it for NLP tasks, and stores structured results for further analysis.  

This project showcases how **web scraping + XML parsing + NLP preprocessing** can transform raw biomedical data into structured insights.  

---

## 🛠️ Tech Stack  
- **Python 3.9**  
- **BeautifulSoup4** → XML/HTML parsing  
- **ElementTree** → XML structure parsing  
- **NLTK** → Tokenization, Stopwords, Lemmatization  
- **Pandas** → Structured data storage  

---

## 📂 Project Structure  

```
06_NLP-Web-Scraping/
├─ data/
│  └─ 769952.xml            # Sample XML file
├─ notebook/
│  └─ 06_NLP_Web_Scraping.ipynb  # Main notebook (end-to-end)
├─ results/
│  ├─ cleaned_text.txt       # Clean article body text
│  └─ article_data.csv       # Final structured dataset
├─ requirements.txt
└─ README.md
```

---

## ⚙️ How to Run  

1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/MedScrapeNLP.git
cd MedScrapeNLP
```

2️⃣ Install dependencies  
```bash
pip install -r requirements.txt
```

3️⃣ Open the notebook  
```bash
jupyter notebook notebook/06_NLP_Web_Scraping.ipynb
```

---

## 📊 Sample Output  

**Extracted Metadata (CSV Preview):**
| article_id      | journal_title        | article_title                                 | author      | publication_date | keywords |
|-----------------|----------------------|-----------------------------------------------|-------------|-----------------|----------|
| 0901c79180555528 | Orphan Drug Approvals | FDA Grants Orphan Drug Status to Gevokizumab | Troy Brown | 29-08-2012 | choroiditis,cyclitis,intermediate uveitis,orphan drugs... |

**Cleaned Tokens (First 20):**  
`['august', '2012', 'us', 'food', 'drug', 'administration', 'fda', 'granted', 'orphan', 'drug', 'status', 'gevokizumab', 'xoma', 'monoclonal', 'antibody', 'binds', 'strongly', 'interleukin', 'β', 'uveitis']`

---

## 🚀 Future Improvements  
- Batch parsing of **multiple XML articles**  
- Advanced **keyword extraction / topic modeling**  
- Integration with **Named Entity Recognition (NER)** for biomedical terms  

---

## 👨‍💻 Author & Branding  
**Developed by: Mubasshir Ahmed**  
📌 Data Science Enthusiast | NLP Explorer | AI Learner  
🔗 [GitHub](https://github.com/mubasshirahmed-3712) | [LinkedIn](https://www.linkedin.com/in/mubasshirahmed3712/)  

---
⭐ If you found this project useful, don’t forget to **star this repo** and connect with me!  
