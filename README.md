# Proyek Analisis Sentimen Submission - Sentiment Analysis on Block Blast! ✨
In main folder, type these commands:

## Install requirements
```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Run the program
Run all cells in scraper.ipynb first, and then run notebook.ipynb.
In notebook.ipynb, you need to adjust this line to the corresponding path of your csv:
```
url = 'https://raw.githubusercontent.com/aljauzr/pas-submission-dicoding/refs/heads/main/ulasan_aplikasi.csv'
app_reviews_df = pd.read_csv(url)
```
