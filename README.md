# Stock-Market-Analyzer

# How to run:
git clone https://github.com/Savinwc/SMA.git
cd./SMA
python -m venv env1
./env1/Scripts/activate
pip install -r requirements.txt
cd ./StockMarketAnalyzer
python manage.py runserver 0.0.0.0:80

# Summary :
This is a full stack machine learning project that uses Django Framework in its core architecture. It is a server
based project that allows users to signup for our services. We scrape the internet for news pertaining to all stocks
and run sentiment analysis on the news articles. This sentiment along with the past stock data is used to predict
the change in the stock. We are obtaining accuracies of upto 70% on a few stocks. This project utilizes a data-centric architecture with a sophisticated backend data pipelining system for processing.

# Technologies used:
● Django
● HTML CSS JS Jquery Bootstrap Plotly
● Tensorflow Keras
● Scrapy BeautifulSoup4

