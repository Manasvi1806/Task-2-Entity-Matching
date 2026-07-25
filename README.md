# Entity Matching Pipeline in R

# Overview
This project matches products from Amazon and Google datasets using text similarity techniques in R.

# Features
- Cleans and preprocesses product names
- Uses Jaro-Winkler fuzzy matching
- Uses TF-IDF and cosine similarity
- Combines similarity scores to find the best match
- Exports the results to `evaluation.csv`

# Files
- `Task_two.Rmd` – R Markdown source code
- `Amazon.csv` – Amazon product dataset
- `GoogleProducts.csv` – Google product dataset
- `evaluation.csv` – Matching results

# Requirements
Install the required packages:

```r
install.packages(c("dplyr", "stringdist", "tm", "proxy"))
```

## Output
The generated file contains:
- Amazon Product
- Matched Google Product
- Confidence Score
- Matching Reason