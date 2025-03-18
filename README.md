# Book Scraping and Visualization Project

This project scrapes book data (titles, prices, ratings, and images) from a website using Python and `BeautifulSoup`. It organizes the data, generates visualizations of price ranges and ratings with `matplotlib`, and displays the results in a user-friendly web interface. Features include a book recommendation system and price range breakdowns. Scrapes book data (titles, prices, ratings, images) using Python &amp; BeautifulSoup. Generates visualizations with matplotlib and displays results in a web interface. Features recommendations and price breakdowns. Built with Python, HTML, CSS, JS.

---

## Features
- Web Scraping: Extracts book details from a catalog.
- Data Visualization: Generates histograms for price ranges and ratings.
- Web Interface: Displays featured books, recommendations, and price statistics.
- Image Downloading: Stores book cover images locally.

---

## Technologies Used
- Python: Scraping, data processing, and visualization.
- BeautifulSoup: HTML parsing and data extraction.
- Matplotlib: Visualizing price ranges and ratings.
- HTML/CSS/JavaScript: Web interface and interactivity.

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/book-scraping-project.git
   ```
2. Install dependencies:
   ```bash
   pip install beautifulsoup4 requests matplotlib pandas numpy
   ```
3. Run the Python script:
   ```bash
   python index.py
   ```
4. Open `index.html` in your browser to view the web interface.



## Project Structure

book-scraping-project/
├── images/              # Book cover images
├── BooksToScrape.html   # Web interface
├── index.py             # Python scraping script
└── README.md            # Project documentation
