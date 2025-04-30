# Job Scraper Tool

The Job Scraper Tool automates the process of searching and extracting remote job listings from various websites. With this tool, users can specify job titles, filter by location, and scrape job details like titles and links, which are useful for job seekers looking for remote opportunities.

## Features
- **Job Title Search** – Specify multiple job titles for scraping.
- **Location Filtering** – Filters for "Work from Anywhere" (WFA) or REMOTE.
- **Duplicate Detection** – Avoids duplicate listings.
- **Automated Scraping** – Gathers titles and job links.
- **Easy Integration** – Built in Python with Selenium.

## Usage
1. Set up ChromeDriver on your system and update the path in the code.
2. Add your job titles inside the `job_titles` list in `config.py`.
3. Run the scraper:
   ```bash
   python main.py
