# scraping-project

- Project uses "Scrappy" [Scrappy](https://scrapy.org/) for crawling and extracting data
- The quickstart is followed by [Build a Web Scraper with MongoDB](https://www.mongodb.com/basics/how-to-use-mongodb-to-store-scraped-data)
- CI/CD is set by [How to Integrate GitHub Actions and CI/CD With Your Next Python Project](https://hackernoon.com/how-to-integrate-github-actions-and-cicd-with-your-next-python-project)

## Usage

- activate virtual environment: `source env-scrapy-mongodb/bin/activate`

- install dependancies: `python -m pip install scrapy ​​'pymongo[srv]'`

- crawl data: `scrapy crawl quotes`
