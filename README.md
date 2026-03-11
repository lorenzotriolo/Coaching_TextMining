# ⚽ NLP & Sentiment Analysis in Youth Soccer Training

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-green)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-orange)
![LaTeX](https://img.shields.io/badge/LaTeX-Report_Generation-008080)

## 📌 Project Overview
This repository contains a **Data Science and Natural Language Processing (NLP)** project applied to a non-conventional domain: youth soccer coaching. 

As the volunteer Head Coach of the **ASO Cernusco U-12 team (born in 2014)**, I systematically documented my post-training evaluations during the first half of the 2025/2026 season. This period marked a critical developmental phase for the players: the transition from 7-a-side to 11-a-side soccer. 

Instead of relying solely on physical metrics, this project applies **Text Mining** and **Transformer-based Sentiment Analysis (BERT)** to my unstructured textual logs to:
1. Quantify the team's emotional and disciplinary trends over time.
2. Evaluate the impact of player attendance on training quality.
3. Objectively track the pedagogical and tactical progression across training microcycles.

## 🚀 Key Features & Analyses
* **Longitudinal Sentiment Analysis:** Utilizing the `neuraly/bert-base-italian-cased-sentiment` model to extract a continuous *Sentiment Score*, acting as an "emotional electrocardiogram" of the season.
* **Attendance vs. Quality (The "Law of Attendees"):** A scatter plot and linear regression analyzing the correlation between the number of players present and the overall mood of the session.
* **Tactical Ontology Tracking (Regex):** Custom Regular Expressions used to aggregate synonyms and soccer jargon (e.g., *terzo uomo*, *giropalla*, *SSG*) to generate a Heatmap, validating the educational progression towards the 11-a-side format.
* **Lexical Frequencies:** A Wordcloud highlighting the coach's primary instructional focus and pedagogical vocabulary.

## 🧠 Methodology & Tech Stack
1. **Data Preprocessing:** Cleaning textual data, handling Italian stopwords, and incorporating domain-specific soccer jargon.
2. **Transformer Models:** Implementation of Hugging Face's pipeline for contextual sentiment extraction from Italian text.
3. **Data Visualization:** `Matplotlib` and `Seaborn` were used to generate heatmaps, scatter plots, and time-series graphs.
4. **Academic Reporting:** The final findings are compiled into a formal, two-column scientific paper using `LaTeX`.

## 📂 Repository Structure
* `Considerazioni allenamenti/` : Contains the anonymized CSV file with the training logs.
* `CoachingNLP/` : Jupyter Notebook / Google Colab file containing the Python code for data processing, BERT implementation, and visualization.
* `Coaching_Sentiment_Analysis/` : The LaTeX source code and the final compiled `.pdf` report.

## 🏃‍♂️ How to Run
1. Clone this repository.
2. Install the required dependencies: `pip install pandas matplotlib seaborn transformers wordcloud nltk`.
3. Run the Jupyter Notebook to generate the analyses and export the images.

## 👨‍🏫 About the Author
I am a Data Science student and a volunteer Head Coach in the Italian grassroots CSI circuit. I'm deeply passioned about sports and analytics and this project aims to connect the dots. science.
