# news_scraping
Script scraping new from "El Pais" website. Saves the data in a Postgres DataBase stored into a AWS T3.micro EC2 instance.

## Scripts

1. **web_scrapping.ipynb:** this script scraps 200+ news from "El Pais" website and stores the data in the Postgres DataBase.
2. **db_wrangling.ipynb:** this script pulls the Postgres DataBase and performs a Sentiment and Subjectivity analysis. Then updates the database with the new data.

## Dependencies

1. requests
2. json
3. re
4. BeautifulSoup
5. Pandas
6. NumPy
7. psycopg2
8. nltk
9. textblob

### Contact
- Jesus Castrejon: jcastrejon@ciencias.unam.mx
