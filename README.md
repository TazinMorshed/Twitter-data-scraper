# Twitter Scraper

## Scape tweets from twitter.com/BBC bangla

#### Made for the Python recruitment process at Technometrics Limited

This scraper is built from scatch using:

- Browser == Microsoft Edge
- Python == 3.9.12
- Selenium == 4.6.0
- Pandas

## Scraping Feature

- Tweet posts &check;
- Tweet posts URL &check;
- Tweet post time &check;
- Tweet text &check;
- Number of comments &check;
- Number of Retweets &check;
- Number of Likes &check;
- Commenter's Name &check;
- Commenter's profile URL &check;
- Comment time &check;
- Comment text &check;
- Retweeter's name &check;
- Retweet Text &check;
- Retweeter's URL &check;

## Scraping Structure

Through this code, we can extract both English and Bengali tweets, and directly store it in mysql database and generate json file if required. For this projects, I have excluded offensive content.

## Database Architecture

Create data base using:

```bash
    create database twitter-db
```

### Tables

##### tweet

![Alt text](assets/df_tweets.png?raw=true "df_tweet")

##### user_data

![Alt text](assets/df_user.png?raw=true "df_user")

##### comment_data

![Alt text](assets/df_comments.png?raw=true "df_comments")

##### retweet_data

![Alt text](assets/df_retweets.png?raw=true "df_retweets")

## Installation

Dowload and install anaconda using 'https://www.anaconda.com/products/distribution'

- Install python 3.9.12
- Install selenium 4.6.0
- Install mysql 8.0.31
- Install pymysql
- Install mysql-connector-python

### For connecting to database:

```sh
conn = msql.connect(host='localhost', user='#username',database='#database_name',
                        password='#password')
```

## What it looks like inside the database:

![Alt text](assets/inside_database.png?raw=true "inside database")

## 🔗 Reach out

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tazin-morshed-b441a6237/)
