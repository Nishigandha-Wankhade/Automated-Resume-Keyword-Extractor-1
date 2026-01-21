<img width="1536" height="1024" alt="ChatGPT Image Jan 18, 2026, 02_56_44 PM" src="https://github.com/user-attachments/assets/6893b06d-7773-43be-940a-1226239dc081" />


### About project

**Category:** NLP | Text Analytics | HR Tech

**Status:** Completed (Mini Project)

**Tech Stack:** Python, Regex, Pandas (optional), Jupyter Notebook

**Input:** Plain text resume

**Output:** Extracted keywords for shortlisting support

**GitHub Link:** https://github.com/Nishigandha-Wankhade/Automated-Resume-Keyword-Extractor-1/tree/main

---

## Project Overview

Built a lightweight NLP-based tool that extracts important keywords from resume text to support faster candidate shortlisting. The project demonstrates how simple text processing can convert unstructured resume content into structured keyword signals useful for recruiters and HR screening.

## Problem Statement

Recruiters often receive large volumes of resumes. Manually scanning them is time-consuming and inconsistent.

This project aims to automate the first screening step by identifying key terms such as:

- Skills
- Tools and technologies
- Job-related keywords
- Relevant domains

## Architecture

<img width="1536" height="1024" alt="ChatGPT Image Jan 18, 2026, 02_51_00 PM" src="https://github.com/user-attachments/assets/ea64c3e5-890e-48bb-b2b5-0be29ea3313f" />


## Solution Overview

Created a keyword extraction workflow that:

- Accepts resume content as plain text
- Cleans and normalizes the text
- Extracts relevant keywords using rule-based logic
- Outputs a shortlist-friendly keyword list

This approach provides a simple foundation for building a more advanced resume parsing system later.

---

## How It Works

1. **Text input** (resume copied as plain text)
2. **Preprocessing** (lowercasing, removing noise, normalizing spaces)
3. **Keyword matching** using:
    - curated keyword lists (skills, tools, roles)
    - pattern matching (regex)
4. **Keyword output** as a structured list

---

## Performance & Results

- Successfully extracts skills and relevant terms from resume plain text input
- Produces consistent keyword output that can be used for:
    - candidate shortlisting
    - matching with job descriptions
    - quick resume summarization
- Lightweight and fast. Designed as a practical mini-tool rather than a heavy ML pipeline

## Results

- Successfully processed **plain-text resume input** and converted unstructured text into structured insights
- Extracted **23 meaningful tokens** after preprocessing and noise removal
- Identified **11 named entities**, including companies, skills, and key terms
- Correctly matched **4 core technical skills** relevant for candidate shortlisting
- Demonstrated a complete NLP pipeline covering:
    - Text preprocessing
    - Tokenization
    - Named Entity Recognition (NER)
    - Skill extraction

This project validates how even a lightweight, rule-based NLP approach can significantly reduce manual resume screening effort.

---

## Example Output. Resume Keyword Extraction

### Input Resume (Plain Text)

```
John Doeis a Data Scientistwith expertisein Machine Learning, Python,andSQL.
He has worked at Googleand Amazon, focusingon NLPand Deep Learning applications.
Heis proficientin Power BIand Snowflakefor data analysis.

```

---

### Extracted Results Summary

| Category | Output |
| --- | --- |
| Tokenized Words | John, Doe, Data, Scientist, expertise, Machine, Learning, Python, SQL, worked, Google, Amazon, focusing, NLP, Deep, Learning, applications, proficient, Power, BI, Snowflake, data, analysis |
| Named Entities | Google, Amazon, Deep Learning, Snowflake, NLP, Python, SQL, John, Doe, Machine, Power |
| Skills Matched | Python, SQL, NLP, Snowflake |
| Sentences Identified | 3 |

---

### Interpretation

- **Skills** were accurately extracted from descriptive text rather than structured lists
- **Company names** were successfully identified for experience context
- Demonstrates feasibility of automated keyword extraction for resume shortlisting
- Highlights areas for enhancement such as reducing noisy entities via advanced NLP models

---

## How Recruiters or Teams Can Use This

- Quickly screen resumes for required skills
- Match resumes against job descriptions
- Reduce manual resume review time
- Serve as a foundation for a resume parsing or ATS-style system

---

## Visual Evidence

- Screenshot of sample input resume text
- Screenshot of extracted keyword output
- Optional: keyword frequency table if present in notebook

---

## Key Learnings

- Turning unstructured text into structured signals is highly valuable for screening workflows
- Rule-based extraction is a strong baseline before introducing ML methods
- Clear preprocessing improves extraction quality significantly

---

## Future Improvements

- Support PDF and Word resumes using `pdfminer` and `python-docx`
- Convert to a web app using **Flask** or **Streamlit**
- Improve extraction using:
    - TF-IDF keyword scoring
    - spaCy NER and skill/entity extraction
    - job description matching and similarity scoring

---
