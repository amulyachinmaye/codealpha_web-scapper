# codealpha_web-scapper
A Python web scraping project that extracts book data (title, price, availability) from BooksToScrape.com. The scraper uses requests, BeautifulSoup, and saves the results into a CSV file. Ideal for learning and showcasing basic web scraping skills.
# 📘 Web Scraping Project: Books to Scrape

This project demonstrates a basic web scraping task using Python. It scrapes book data from the [BooksToScrape.com](https://books.toscrape.com) demo website.

## 🔍 What It Does
- Scrapes book **titles**, **prices**, and **availability** from the first page
- Uses `requests` to download HTML and `BeautifulSoup` to parse it
- Saves the extracted data into a CSV file (`books.csv`)

## 🧰 Tools Used
- Python 3
- requests
- BeautifulSoup (bs4)
- csv (Python standard library)

## 📁 Output
A file named `books.csv` containing data like:

| Title                       | Price  | Availability |
|----------------------------|--------|--------------|
| A Light in the Attic       | £51.77 | In stock     |
| Tipping the Velvet         | £53.74 | In stock     |
| ...                        | ...    | ...          |

## ▶️ How to Run
1. Open the Jupyter notebook `simple_book_scraper.ipynb`
2. Run the cells step-by-step
3. The final CSV file will be saved in your working directory

## 💡 Notes
- This project is based on a public demo website, so scraping is allowed
- The code only scrapes data from the first page (20 books)
- No extra libraries or login required

---

✅ **Great for beginner data analysts and interns looking to showcase scraping skills!**
