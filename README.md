# Automated News Summarizer

An AI-powered web application built with Flask that automatically condenses lengthy news articles, blogs, and documents into concise, context-rich summaries.  
It supports text input, file uploads (`.txt`, `.docx`, `.pdf`), and URL-based content extraction via web scraping.  
The summarization engine offers both Extractive (TextRank) and Abstractive (T5/BART) methods to suit different needs.

---

## Features

Multiple Input Methods
- Paste raw text
- Upload `.txt`, `.docx`, or `.pdf` files
- Provide a URL for automated content scraping

Two Summarization Modes
- Extractive – Selects and ranks key sentences using the TextRank algorithm
- Abstractive – Generates paraphrased summaries using Transformer models (T5, BART)

Extra Capabilities
- View original text and summary side by side
- Download generated summaries for offline use

---

##  Tech Stack

Frontend: HTML, CSS, JavaScript  
Backend: Flask (Python)  
Core Libraries & Tools:
- BeautifulSoup, Requests – Web scraping & content fetching  
- NLTK, Scikit-learn, NetworkX – NLP & TextRank algorithm  
- HuggingFace Transformers – Abstractive summarization (T5, BART)  
- python-docx, PyPDF2 – File handling  

---

##  Installation & Usage

1. Clone the repository
```bash
git clone https://github.com/your-username/automated-news-summarizer.git
cd automated-news-summarizer
```
2. Create a virtual environment
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies
   pip install -r requirements.txt
4. Run the application
   python app.py
   Then open your browser at http://127.0.0.1:5000
   
## Performance Notes
Extractive mode: Fast, preserves original sentence structure
Abstractive mode: Slower but produces more natural, human-like summaries
Performance depends on text length and method used

## License
This project is licensed under the MIT License – free to use, modify, and distribute.

## Authors
Shreya Sriram, Shruti Sivakumar, Vida Nadheera S

