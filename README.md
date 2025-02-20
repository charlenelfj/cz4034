# CZ 4034 Infomation Retrieval

This application is powered by Django and Solr, serving as a mini search engine, whereby users can type in any keywords and the application will return relevant results, in the form of instagram captions and images that are retrieved from various news profiles.

It offers users the option to filter by the news channels that they want to see and also by categories as well. Users can also choose to sort by default, most recent and most number of likes on the post.

## Installation
Make sure you have the following components before running, or you can install them.
1. Python 3.7.6
2. Django 3.0.4
3. BeautifulSoup4
4. Selenium 3.9.0
5. Tqdm 4.23.4
6. Webdriver_manager
7. Solrpy 0.9.9

## Running the application
1. Clone/download this repository
2. Change directory to the path .../solr-8.4.1/solr-8.4.1/bin (windows) or .../solr-8.4.1/solr-8.4.1 (mac os)
3. Enter `solr.cmd start` (windows) or `bin/solr start` (mac os); you should see a confirmation message that solr has started running.
4. Change directory to the path ../CZ4034
5. Enter `python manage.py runserver` and you should see that Django has started.
6. Open a browser and navigate to the following link: http://127.0.0.1:8000/

## Screenshots
![Home page](home-page.png)
![search result](search-result.png)
![spelling-correction](spelling-correction.png)

### Happy searching!

