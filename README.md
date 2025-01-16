# GitHub Topics and Repositories Scraper

## Project Overview
This project is a web scraper designed to extract data from GitHub's Topics and Repositories pages. The primary goal is to collect information on popular GitHub topics and the repositories associated with them, making it easier to analyze trends, explore open-source contributions, and gather useful insights.

The project is implemented in Python using Jupyter Notebook and utilizes popular libraries like `requests`, `BeautifulSoup`, and `pandas` for web scraping and data handling. The extracted data can be exported in a structured format, such as CSV, for further analysis.

---

## Project Description
The project automates the process of gathering data from GitHub, focusing on:

1. **GitHub Topics Page**:
   - Extracts the list of topics displayed on GitHub's Topics page.
   - Retrieves metadata such as topic name, description, and the URL to the topic's repository list.

2. **Repositories Within Each Topic**:
   - For each topic, scrapes the associated repositories.
   - Gathers repository-specific data such as:
     - Repository name.
     - Author/organization name.
     - Number of stars.
     - Repository link.

The scraped data can be stored in a structured DataFrame and saved to a CSV file for easy analysis or integration into other workflows.

---

## Project Outline
1. **Setup and Installation**:
   - Install required Python libraries:
     ```bash
     pip install requests beautifulsoup4 pandas
     ```
   - Clone the repository:
     ```bash
     git clone https://github.com/Rsivamani/GitHub-Topics-and-Repositories-Scraper.git
     ```

2. **Run the Notebook**:
   - Open `web_scrapping_scratch_py.ipynb` in Jupyter Notebook.
   - Execute cells sequentially to scrape data and generate results.

3. **Features**:
   - Scrape data from the GitHub Topics page.
   - Extract detailed information on repositories within each topic.
   - Save results to CSV for analysis.

4. **Expected Output**:
   - A CSV file containing a list of topics and their associated repositories with metadata.

---

## Tools and Acknowledgements
### Tools Used:
- **Programming Language**: Python
- **Libraries**:
  - `requests`: For making HTTP requests to GitHub pages.
  - `BeautifulSoup`: For parsing HTML and extracting data.
  - `pandas`: For data manipulation and storage.

### Acknowledgements:
- **GitHub**: For providing access to publicly available data on topics and repositories.
- **Python Community**: For maintaining the open-source libraries used in this project.

---

