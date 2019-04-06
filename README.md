# Music-Mood
## Usage
Install requirements
```bash
pip install -r requirements.txt
```

Run Server
```bash
python app.py
```

## Classifier Information - V1
* Model : **Support Vector Machine**
  * Training F1 : 0.997
  * Validation F1 : 0.712

* Method : TFIDF - Vectorizer 
  * Stopwords : English
  * N-Gram Range : (1,5)


## Codelabs

<https://docs.google.com/document/d/1OBAT-QbOBtAnemFEvrON5qbgDmJfVypnWI3umtzKsTI/edit?usp=sharing>

## Built With

- [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) - Code editor used for python
- [IBM Watson Tone Analyzer](<https://www.ibm.com/watson/services/tone-analyzer/>)-API used for analyzing mood of the songs
- [Musixmatch Developer](https://developer.musixmatch.com/)- API used to fetch lyrics for the songs in top charts.
- [Heroku](https://www.heroku.com/) :Cloud Application Platform used to host the website
- [Flask](http://flask.pocoo.org/) :Microframework in python used to deploy the front end

## Authors

- **Ami Vora** 
- **Juhi Pareek** 
- **Aditya Soni** 
- **Hemin Joshi** 