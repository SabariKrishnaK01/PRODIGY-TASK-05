PRODIGY-TASK-05 - 📚 Book Scraper 

This Python program scrapes book data from [Books to Scrape](http://books.toscrape.com/) — a website specifically created for web scraping practice. It collects the title, price, and rating of books listed on the homepage and saves them to a CSV file.

🔧 Features

-  Extracts book title, price (£), and rating (e.g., Three, Five).
-  Exports data into a clean `books.csv` file.
-  Uses lightweight and efficient libraries (`requests`, `BeautifulSoup`, `csv`).
-  Simple, beginner-friendly structure

🧠 Concepts Demonstrated

- Web scraping with **BeautifulSoup**
- Sending HTTP requests using **requests**
- Working with **CSV file output**
- **HTML parsing** and navigating DOM elements using CSS selectors
- String manipulation in Python

💻 How It Works

1. Sends a GET request to the homepage.
2. Parses HTML content using BeautifulSoup.
3. Loops through each book element and extracts:
   - 📘 Title
   - 💷 Price
   - ⭐ Rating
4. Writes the collected data into `books.csv`.

📥 Sample Output (books.csv)

