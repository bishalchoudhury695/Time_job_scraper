# Time_job_scraper

This is a simple web scraping project that automatically searches for Python-related jobs on the TimesJobs website. The script scrapes job listings and saves details of recent postings (jobs posted within the last few days) into text files.

## Features

- Scrapes job listings for Python-related jobs from TimesJobs.
- Filters out jobs that require unfamiliar skills (e.g., React).
- Saves job details, such as company name, required skills, and a link for more information into individual text files.
- Automatically repeats the job search every 1 minute.

## Requirements

Make sure you have the following installed:

- Python 3.x
- Required Python libraries (`requests`, `bs4`, `time`, `os`)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/python-job-scraper.git
   cd python-job-scraper
