# 📓 Daily Sentence Journal Analysis

## Overview
In 2018, I started an iPhone note title "Daily Sentence 2018" - it became a simple log of short daily summaries.
Jump forward to today and this is the perfect corpus for experimenting with Natural Language Processing (NLP), time series analysis, and predictive modeling.
What began as a casual journaling habit has become a personal data science project. This repository contains a full data science pipeline built on my personal journaling data.  

---

## Data Format

The data has been hidden on this repo because it contains personal information, but the format is simple.
- Each note corresponds to a year with the format being "Daily Sentence XXXX" (e.g. Daily Sentence 2018, Daily Sentence 2019, ...)
- Each entry includes a `date` (MM/DD) and one or more sentences `sentence`. Simple

Example:
```
10/3 – Ate ramen with friends. Saw Avatar afterwards.
10/4 – Went to work, ate chipotle then visited John's house.
```

---

## Setup
```
python3 pip install transformers torch seaborn
```

## 🗂️ Repository Structure

