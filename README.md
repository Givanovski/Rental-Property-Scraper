# Rental Property Scraper and Google Form Submission

This project is a Python script that scrapes rental property listings from a Zillow clone website and submits the scraped data to a Google Form. The main objectives are to collect rental properties' links, addresses, and prices and automate the data entry process.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Scrapes rental property links, addresses, and prices from a Zillow clone website.
- Cleans and formats the scraped data for submission.
- Utilizes BeautifulSoup for web scraping and Selenium for automating the form submission.
- Handles up to 5 entries in a single run.

## Technologies Used

- **Python**: The main programming language for the script.
- **Beautiful Soup**: A library for web scraping HTML and XML documents.
- **Requests**: A library for making HTTP requests to fetch web pages.
- **Selenium**: A web automation tool for filling out the Google Form.
- **Google Forms**: The platform used for data entry.

 ## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Givanovski/Rental-Property-Scraper.git
   cd Rental-Property-Scraper
   
2. **Install Required Packages: Make sure you have Python installed, then install the required packages**:
   ```bash
   pip install beautifulsoup4 requests selenium
   
3. **Set Up WebDriver**: Ensure you have the Chrome WebDriver installed and in your system's PATH. You can download it from ChromeDriver.
  
4. **Run the script**:
   ```bash
   python main.py
5. **The script will scrape the data from the Zillow clone website and automatically fill in the Google Form for the first 5 entries**.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please fork the repository and submit a pull request.







