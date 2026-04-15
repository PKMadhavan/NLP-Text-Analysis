# NLP Text Analysis

This repository contains a Jupyter notebook for basic Natural Language Processing (NLP) tasks on plain text files. It includes text preprocessing, tokenization, contraction expansion, frequency analysis, and Zipf’s Law visualization.

## Project Overview

The notebook processes raw text data and performs several common NLP operations, such as cleaning text, splitting it into paragraphs, sentences, and tokens, and generating statistical summaries. It also examines word frequency distributions and visualizes Zipf’s Law to show the relationship between word rank and frequency.

## Repository Structure

```text
NLP-Text-Analysis/
├── Text Analysis.ipynb
├── data/
│   ├── Anime.txt
│   └── war-and-peace.txt
└── output/
    ├── output1.txt
    └── output2.txt
```

## Features

- Text cleaning and preprocessing  
- Sentence and word tokenization  
- Contraction expansion  
- Paragraph, sentence, and token statistics  
- Word frequency counting  
- Zipf’s Law plotting and analysis  

## Requirements

Install the required Python libraries before running the notebook:

```bash
pip install numpy matplotlib nltk
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PKMadhavan/NLP-Text-Analysis.git
   cd NLP-Text-Analysis
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open `Text Analysis.ipynb` and run the cells in order.

## Notes

- Input text files are stored in the `data/` folder.  
- Generated results are stored in the `output/` folder.  
- If file paths are changed, update them in the notebook accordingly.
