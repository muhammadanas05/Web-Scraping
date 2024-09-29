# LinkedIn Job Scraping using Selenium

This repository contains a Python script that automates the process of scraping job listings from LinkedIn using Selenium. The script specifically targets jobs in your region and extracts key details such as the company name, job title, and job links. All extracted data is saved in a CSV file for easy access and analysis.

## Features
- **Scrape Job Listings**: The script scrapes job titles and associated company names for jobs posted in a specified region.
- **Extract Job Links**: It also extracts the URLs for all available job listings, enabling direct access to the job application page.
- **Save Data to CSV**: The scraped data, including job titles, company names, and job links, is stored in a CSV file for further analysis or reference.

## How It Works
1. ### Selenium Setup: The script uses the Selenium WebDriver to interact with LinkedIn’s job listings page.
2. ### Extract Data: It scrapes the following job details:
   - Job Title: The title of each job posting.
   - Company Name: The name of the company offering the job.
   - Job Links: The direct link to the job listing for quick access.
3. ### CSV Output: The extracted data is saved in two CSV files:
   - linkedin.csv: Contains job titles and company names.
   - linkedinlinks.csv: Contains links to all available job listings.

## Prerequisites
- Python
- Selenium
- ChromeDriver (or another WebDriver of your choice)
- Google Chrome (Ensure the version matches your ChromeDriver version)



## Contributing
Feel free to submit pull requests or open issues to improve this project. Contributions are welcome!

---

This README provides an overview of the project and its purpose, explains how to set it up, and shows what kind of data the script extracts.