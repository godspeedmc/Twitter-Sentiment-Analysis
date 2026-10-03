# Twitter Sentiment Analysis

A machine learning project for classifying the sentiment of tweets into four categories:

- Positive
- Negative
- Neutral
- Irrelevant

This project uses a labeled Twitter dataset and processes text before training a sentiment classification model. The notebook demonstrates exploratory data analysis, text preprocessing, feature extraction, model training, and evaluation.

## Project objective

The goal is to build a text classification pipeline that can analyze social media posts and predict their sentiment polarity. This is useful for brand monitoring, customer feedback analysis, and understanding public opinion about a topic or company.

## Dataset

The notebook uses a Twitter entity sentiment dataset downloaded through KaggleHub.

Key data columns:

- `id`: tweet identifier
- `country`: associated entity/topic
- `Label`: sentiment label
- `Text`: tweet content

The dataset contains thousands of tweet samples and includes multiple sentiment classes.

## Workflow

The notebook includes the following steps:

1. Loading the dataset
2. Checking data shape and missing values
3. Exploring label distribution
4. Cleaning and preprocessing tweet text
5. Applying NLP transformations such as stopword removal and lemmatization
6. Splitting data into training and test sets
7. Converting text to features using TF-IDF
8. Training a machine learning classifier
9. Evaluating metrics such as accuracy and classification report

## Technologies used

- Python
- Pandas
- NumPy
- scikit-learn
- spaCy
- KaggleHub
- Jupyter Notebook

## File in this repository

- `Twitter_Sentiment_Analysis.ipynb` — main notebook containing the full analysis and model pipeline

## Setup

You can run the notebook in either Jupyter or Google Colab.

### Python dependencies

```bash
pip install pandas numpy scikit-learn spacy kagglehub
```

If needed, download the English spaCy model:

```bash
python -m spacy download en_core_web_sm
```

## Run the project

Open the notebook and execute the cells sequentially.

If you are using Colab, upload the notebook and run it in the notebook environment.

## Example use case

This project can be extended to:

- analyze brand sentiment on social media
- monitor customer reactions in real time
- detect harmful or negative discussion patterns
- classify posts for dashboard reporting

## Notes

- The notebook is designed as an educational and exploratory ML project.
- Results may vary depending on the dataset version and model configuration.
- The project is a good starting point for learning NLP-based sentiment classification.

## License

This project does not currently include a formal license file. If you plan to share or reuse it publicly, consider adding an open-source license appropriate for your use case.
