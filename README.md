# NLP Assignment — Text Preprocessing (Corrected Submission)

**Name:** PATAN KHALILULLA KHAN

⚠️ **Correction note:** this replaces the earlier upload (which contained the
SVM/Trees/Ensembles ML assignment). This submission contains the required
**NLP Text Preprocessing** deliverable: ONE Jupyter notebook.

## Contents

| File | Purpose |
|---|---|
| `NLP_Text_Preprocessing_PatanKhalilullaKhan.ipynb` | **Main deliverable** — single notebook, all tasks, executed with outputs |
| `text_data.csv` | Input text dataset (30 intentionally messy social-media style texts) |
| `nlp_preprocessed_output.csv` | Output of the full pipeline (regenerated when the notebook runs) |
| `README.md` | This file |

## Tasks implemented (per feedback checklist)

1. Load text dataset with Pandas, print samples/length, identify text issues
2. Basic cleaning → `clean_text_basic`
3. Advanced cleaning (URLs, e-mails, HTML, special chars/emojis) → `clean_text_advanced`
4. NLTK stopwords → `text_no_stopwords`
6. Word & sentence tokenization
7. Porter/Snowball stemming vs original words
8. WordNet lemmatization vs stemming
9. `nlp_preprocess(text)` pipeline → `final_clean_text`
10. Documented observations (markdown in notebook)

## Run

```bash
pip install pandas nltk
jupyter notebook NLP_Text_Preprocessing_PatanKhalilullaKhan.ipynb
```
Run all cells top-to-bottom; NLTK resources download automatically.
