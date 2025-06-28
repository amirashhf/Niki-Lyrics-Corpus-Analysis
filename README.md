# 🎤 Lexical Analysis of NIKI's Song Lyrics (A Corpus Study)

![Corpus Linguistics](https://img.shields.io/badge/Corpus-Linguistics-blue.svg)
![NLP](https://img.shields.io/badge/NLP-Lexical_Analysis-green.svg)
![AntConc](https://img.shields.io/badge/Tool-AntConc-orange.svg)

## 📖 Overview
Nicole Zefanya, known professionally as NIKI, has gained international acclaim for her introspective and narrative songwriting. This project conducts a corpus-based lexical analysis of her song lyrics from two pivotal albums, **"Nicole" (2022)** and **"Buzz" (2024)**. Using the corpus analysis toolkit **AntConc**, this study systematically identifies and analyzes the key lexical characteristics that define her unique poetic and emotional style, revealing how word choice and recurring phrases build her signature themes of love, loss, and self-reflection.

## 📊 The Corpus
* **Content:** The corpus consists of **25 song lyrics** from NIKI's albums "Nicole" and "Buzz".
* **Source:** Lyrics were manually collected from AZLyrics and saved as individual `.txt` files.
* **Size:** The corpus contains **7,636 tokens** (total words) and **1,401 types** (unique words).

## ⚙️ Analytical Workflow
The analysis was performed using **AntConc** with the following systematic approach:

1.  **Corpus Compilation:** All 25 `.txt` lyric files were loaded into AntConc.
2.  **Word Frequency Analysis:** A word list was generated to identify the most frequent and significant content words.
3.  **Keyword Analysis:** Five key thematic words (**LOVE, FEEL, KNOW, LIFE, TIME**) were selected for in-depth analysis based on their frequency and thematic relevance.
4.  **Concordance (KWIC) Analysis:** The "Key Word in Context" (KWIC) was examined for each keyword to understand its usage patterns and semantic functions.
5.  **Collocation & N-Gram Analysis:** Collocates (frequently co-occurring words) and N-grams (recurring multi-word phrases) were analyzed to identify characteristic lexical bundles and phrases.

## 🔑 Key Lexical Findings

The analysis revealed several defining lexical characteristics in NIKI's songwriting:

* **Introspective & Conversational Tone:** The lyrics are dominated by a **first-person perspective** (high frequency of `I`, `my`, `me`) and a conversational style, evidenced by the frequent use of contractions (`'s`, `'t`, `'m`).
* **Themes of Uncertainty:** Negative phrases, particularly **`i don't know`** and its variants (`i don t`, `i won t`, `i can t`), are among the most frequent N-grams. This strongly underscores the recurring themes of personal uncertainty, doubt, and introspection.
* **Complex View of Love:** The keyword **`LOVE`** is used to explore a realistic and often ambivalent cycle of love, highlighted by patterns like "fall in love" and the "love-hate" concept, rather than a purely idealized view.
* **Exploration of Internal States:** The keyword **`KNOW`** is central to exploring self-awareness and doubt, while **`FEEL`** is used to articulate complex and often contradictory emotional states.
* **Metaphorical Language:** Abstract concepts like **`LIFE`** and **`TIME`** are often explored through strong metaphors, such as *"Life is a gamble"* or the desire to *"stop time"*.

![image](https://github.com/user-attachments/assets/ca440f80-86a9-437f-86f1-40e21068f8e1)


## 🚀 How to Replicate This Analysis

1.  **Download and install** [AntConc](https://www.laurenceanthony.net/software/antconc/), a freeware corpus analysis toolkit.
2.  **Clone this repository** to get the corpus files.
3.  **Load the Corpus:** Open AntConc, go to `File > Open Dir...`, and select the folder containing the `.txt` lyric files from this repository.
4.  **Perform Analysis:** Use the built-in tools like `Word List`, `Concordance`, `Collocates`, and `N-Grams` to explore the data and replicate the findings.
