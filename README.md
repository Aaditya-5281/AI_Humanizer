#  Text Humanizer    
A lightweight app that transforms AI-generated or casual text into polished, academic-style writing. Perfect for students, researchers, and professionals who want their text to sound more natural and formal.


##  Installation  

###  Clone the Repository  
```bash
git clone https://github.com/Aaditya-5281/AI_Humanizer.git
cd AI_Humanizer
```

### Set Up a Virtual Environment (Recommended)  
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### Install Dependencies  
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### Download NLP Models  
```bash
python -m spacy download en_core_web_sm
python -c "import nltk; nltk.download('punkt'); nltk.download('wordnet'); nltk.download('averaged_perceptron_tagger');"
```

---

## 🖥️ Usage  

### 🎯 **Run the Streamlit Web App**  
```bash
streamlit run main.py
```
- This will **open a browser** at `http://localhost:8501`   

