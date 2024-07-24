# NewsScraper

`NewsScraper` is an R package designed to scrape news articles for specified companies within a given date range and save the results to an Excel file.   This package is particularly useful for researchers and analysts who need to gather and analyze news data related to specific companies and topics.

## Features

- Scrape news articles from Google News.
- Filter news articles based on specified date ranges.
- Search for news articles using customizable keywords with AND/OR logic.
- Save the scraped news data to an Excel file.

## Output
The scrape_company_news function will generate an Excel file specified by output_file, containing the scraped news articles.  The output file will have the following columns:

- Company. Name: The name of the company.
- Ticker: The ticker symbol of the company.
- Title: The title of the news article.
- Link: The URL link to the news article.
- Publication. Date: The publication date of the news article.

## Clarification
- After testing, this version of the R package has high network and bandwidth requirements, so I'm trying to further optimise the code structure to make it work more consistently.
- Considering that this R package relates to my working project, I can't have open access to this R package until I finish this project.
- If you are interested in this R package, you can contact me directly, my email is LingYUAN1201@outlook.com
