# Crawlbase Custom Crawler Assessment

## Introduction
Welcome to the Crawlbase Custom Crawler Assessment. This test aims to assess your proficiency in Ruby, JavaScript, and C# by tasking you with developing a custom web crawler using the Crawlbase Crawling API.

## Test Instructions

### Overview
You are required to:
1. **Create a Crawlbase Account**: Sign up at [Crawlbase](https://crawlbase.com) and obtain your API key with the 1000 free credits.
2. **Develop a Solution**:
   - **Crawl and Scrape Data** using the provided input TXT file.
   - **Extract Keywords** from the TXT file.
   - **Output** the results into a CSV file.
3. **Technologies**:
   - **Ruby**: Backend scripting and data processing.
   - **JavaScript**: Data processing or utility scripting.
   - **C#**: Data validation and optional enhancements.

### Requirements

#### Input:
- **urls-dev-test.txt**: A text file containing the URLs to be crawled.
- **keywords-dev-test.txt**: A text file with each keyword on a new line.

#### Output:
- **example-output-dev-test.csv**: A CSV file containing keyword matches and metadata found on the scraped web pages. This file serves as an example of the expected output format.

#### Functionality:

1. **Data Parsing**:
   - Read the URLs from the `urls-dev-test.txt` file and scrape them.
   - Process the list of keywords in the `keywords-dev-test.txt` file against the URLs.

2. **Web Scraping**:
   - Implement logic to scrape web pages in the TXT.
   - Implement error handling for cases where scraping fails (e.g., network issues, invalid URLs).

3. **Keyword Matching**:
   - Implement logic to search each scraped web page for the provided keywords.
   - Perform case-insensitive keyword matching.

4. **Output Generation**:
   - Write an output CSV file containing keyword matches found on scraped pages.
   - For each keyword match, the output file should include:
     - The matched keyword (text) in the "Keyword" column.
     - The sentence containing the matched keyword (text) in the "Context" column.
     - The URL of the webpage where the match was found (text) in the "URL" column.
   - If there is no match for a keyword in the target URL, print "No match found" in the "Context" column.

### Steps to Complete

1. **Fork the Repository**
   - Fork this repository to your GitHub account.

2. **Implement the Solution**
   - **Backend (Ruby)**: Develop a script to process the input files and extract keywords.
   - **Utility (JavaScript)**: Use JavaScript for data processing or any required scripting tasks.
   - **Utility (C#)**: Implement a tool for CSV validation and optional features.

3. **Submission**
   - **Documentation**: Include a README with setup instructions and a code overview.
   - **GitHub Repository**: Provide a link to your forked repository with the complete project.

### Example Instructions

- **Ruby Script**: Implement a script to read the input files, fetch data using the Crawlbase API, extract keywords, and save to CSV.
- **JavaScript Utility**: Create a script for any required data processing or utility tasks.
- **C# Validator**: Build a utility to validate the CSV output.

### Assessment Criteria
- **Functionality**: Meets all requirements.
- **Code Quality**: Clean and well-documented.
- **Documentation**: Clear README.
- **Integration**: Effective use of the Crawlbase API.

### Guidelines

- **External Libraries**: You are allowed to use any external libraries for the test, but not AI tools like ChatGPT or similar.
- **Ruby Version**: Please use ruby version 3.1.2.
- **C# Version**: Use C# 10 with .NET 6.0 for the project.

### Optional Enhancements (Extra Credit)

1. **Advanced Keyword Matching**: Implement techniques like stemming or fuzzy matching to improve keyword matching accuracy.
2. **Parallel Processing**: Optimize the scraping process by implementing parallel processing to handle multiple URLs simultaneously, improving efficiency and speed.

### Deadline
Complete and submit your solution within one week of starting the test.

Best of luck! We look forward to your submission!
