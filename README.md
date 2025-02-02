# Text Summarization using Pre-trained Models and TOPSIS Ranking

## Overview

This repository provides an implementation of **text summarization** using **pre-trained NLP models** and evaluates them using **ROUGE scores**. The models are then ranked using the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to determine the best-performing summarization model.

## Features

- Uses state-of-the-art **pre-trained text summarization models**.
- Computes **ROUGE scores** for evaluating the quality of generated summaries.
- Applies **TOPSIS ranking** to compare model performance objectively.
- Includes visualizations of **TOPSIS ranking, inference time, and ROUGE scores**.

## Models Used

The following **pre-trained text summarization models** have been evaluated:

- **facebook/bart-large-cnn**
- **t5-small**
- **t5-base**
- **google/pegasus-xsum**

## Dependencies

To run this project, install the required libraries:

```bash
pip install transformers rouge-score numpy pandas scikit-learn matplotlib
```

## Usage

### Running the Summarization Script

1. Clone the repository:
   ```bash
   git clone https://github.com/Teddyy27/Text_summarization_Topsis.git
   cd <repo-folder>
   ```
2. Run the summarization evaluation script:
   ```bash
   python summarization_topsis.py
   ```
3. The script will generate a **TOPSIS ranking** and save the results in CSV and PNG format.

## Outputs

- **topsis\_ranking.csv**: Contains the TOPSIS ranking scores for each model.
- **summarization\_model\_evaluation.csv**: Contains detailed ROUGE scores for each model.
- **topsis\_ranking.png**: Visualization of TOPSIS scores.
- **inference\_time.png**: Bar chart comparing inference times.
- **rouge\_scores.png**: Comparison of ROUGE-1, ROUGE-2, and ROUGE-L scores.

## Results

The generated **TOPSIS ranking**, **inference time comparison**, and **ROUGE score comparison** can be found in the repository’s media folder. These results help identify the best-performing summarization model.

## Contributions

Feel free to contribute by improving the **summarization models**, adding more **evaluation metrics**, or optimizing the **TOPSIS ranking method**.

## License

This project is licensed under the **MIT License**.

---

**Author:** Arnav Agarwal\
\*\*GitHub Repo: \*\***[https://github.com/Teddyy27/Text\_summarization\_Topsis.git](https://github.com/Teddyy27/Text_summarization_Topsis.git)**

