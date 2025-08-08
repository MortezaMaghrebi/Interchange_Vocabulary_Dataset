# 📚 Interchange Vocabulary Extraction & Preparation Project

This repository contains a curated list of vocabulary extracted from the **Interchange** book series, processed and prepared for English language learning.  
The entire workflow was automated using custom scripts along with NLP tools.

---

## 🛠 Process Overview

1. **Text Extraction from PDF**  
   - The Interchange books were converted into editable text using **PDF OCR**.

2. **New Word Extraction**  
   - A custom-made program extracted all unique words from the text.  
   - Around **2,000 very easy words** were removed from the list.

3. **Dictionary Cross-Check**  
   - The remaining words were compared against a **190,000-word dictionary**.  
   - Words found in the dictionary were marked as “valid words.”

4. **List Cleaning & Optimization** *(using Grok)*  
   - Removed proper nouns.  
   - Removed incomplete or meaningless words.  
   - Preferred singular form over plural.  
   - Merged words with the same root to avoid duplicates.

5. **Adding Learning Data** *(using DeepSeek)*  
   - Persian translation.  
   - Example sentences.  
   - English synonyms or equivalents.  
   - CEFR level.  
   - Pronunciation (IPA or phonetic transcription).

6. **Final Review & Corrections** *(using Grok)*  
   - Reviewed the generated file for accuracy.  
   - Fixed errors and created the final version.

---

## 📂 Repository Contents

- **`final_words_list.csv`** → Final vocabulary list with translation, examples, CEFR level, and pronunciation.  
- **`raw_extracted_words.txt`** → Initial extracted word list before processing.  
- **Scripts & Tools** → For extraction, filtering, and processing.

---

## 🚀 Use Cases

- Learning vocabulary based on the Interchange series.  
- Creating flashcards for apps like Anki or Quizlet.  
- Linguistic analysis and language learning research.

---

## 📜 License
This project is intended for educational purposes.  
Free to use with proper attribution.
