# Web Scraping & Data Handling Challenge

## Project Overview

This project involves web scraping and data handling using Python, Selenium, BeautifulSoup, and Pandas. The goal is to extract, filter, and analyze movie and TV show data from JustWatch, a platform that aggregates content from multiple streaming services.

## Website

- JustWatch: [JustWatch Movies](https://www.justwatch.com/in/movies?release_year_from=2000)

## Project Description

JustWatch allows users to search for movies and TV shows across various streaming services like Netflix, Amazon Prime, Hulu, etc. For this assignment, we will scrape data from JustWatch's website, perform data filtering and analysis, and save the results to a CSV file.

## Tasks

### 1. Web Scraping

**Using BeautifulSoup to scrape the following data from JustWatch:**

#### a. Movie Information
- Movie title
- Release year
- Genre
- IMDb rating
- Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
- URL to the movie page on JustWatch

#### b. TV Show Information
- TV show title
- Release year
- Genre
- IMDb rating
- Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
- URL to the TV show page on JustWatch

#### c. Scope
- Scrape data for at least 50 movies and 50 TV shows.
- Choose an entry point (e.g., starting with popular movies, or a specific genre) to ensure a diverse dataset.

### 2. Data Filtering & Analysis

**After scraping the data, use Pandas to perform the following tasks:**

#### a. Filter movies and TV shows based on specific criteria:
- Only include movies and TV shows released in the last 2 years (from the current date).
- Only include movies and TV shows with an IMDb rating of 7 or higher.

#### b. Data Analysis:
- Calculate the average IMDb rating for the scraped movies and TV shows.
- Identify the top 5 genres with the highest number of available movies and TV shows.
- Determine the streaming service with the most significant number of offerings.

### 3. Data Export

- Save the filtered and analyzed data into a CSV file for further processing and reporting.
- Keep the CSV file in your Drive Folder and share the Drive link on the Colab notebook with view access for anyone.

## Submission

- Submit a link to your Colab notebook for the assignment.
- The Colab notebook should contain your Python script (.py format only) with clear comments explaining the scraping, filtering, and analysis process.
- Ensure your code is error-free and executable in one go.
- Include your Dataset Drive Link in the notebook before the conclusion.

## Note

- Properly handle errors and exceptions during web scraping to ensure a robust script.
- Ensure your code is well-structured, easy to understand, and follows Python best practices.
- The assignment will be evaluated based on the correctness of the scraped data, accuracy of data filtering and analysis, and the overall quality of the Python code.

## Contact

For any questions or clarifications, please contact MOHD ALI KHAN at m.alikhan.data@gmail.com
