# README

## Overview
This repository contains code for evaluating retrieval models on a summarized text corpus. The evaluation is performed using the BM25 and Query Likelihood models on three different summarization models: Led Large, Pegasus, and Distil Bart. The evaluation metrics include Mean Average Precision (MAP), Mean Reciprocal Rank (MRR), and Mean Discounted Cumulative Gain (DCG).

## Files

- **data.json**: Original corpus data in JSON format.
- **output_led_large_text_sum.txt**: Summarized corpus using the Led Large model.
- **pegasus.txt**: Summarized corpus using the Pegasus model.
- **distil_Bart.txt**: Summarized corpus using the Distil Bart model.
- **sample-annotations.json**: Manually annotated data with queries and relevant documents.

## Code Files

- **query_likelihood_model.py**: Implementation of the Query Likelihood model.
- **bm25_model.py**: Implementation of the BM25 model.
- **summarization_evaluation.ipynb**: Jupyter notebook containing the evaluation process.

## Dependencies
Make sure you have the following dependencies installed:

- `json`
- `requests`
- `beautifulsoup4`
- `nltk`
- `rank_bm25`
- `numpy`

You can install these dependencies using the following command:
```bash
pip install json requests beautifulsoup4 nltk rank_bm25 numpy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repository
   ```

3. Run the Jupyter notebook `summarization_evaluation.ipynb` for detailed evaluation and analysis.


## Results

The evaluation results for each summarization model and retrieval model combination are provided in the notebook. Metrics such as MAP, MRR, and DCG are reported for each model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
