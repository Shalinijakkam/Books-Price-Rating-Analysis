# Books Price and Rating Analysis 📚

## Project Overview
An end-to-end data analysis project that scrapes, cleans, analyzes, and visualizes book data from books.toscrape.com to uncover pricing trends and rating patterns across 1,000+ books.

## Business Problem
Retailers and publishers need to understand how book pricing relates to customer ratings — identifying which price ranges attract the best reviews and which genres perform well to guide inventory and pricing decisions.

## Tools & Technologies
- **Python** — BeautifulSoup, Requests, Pandas, Matplotlib, Seaborn
- **Power BI** — Interactive dashboard
- **Jupyter Notebook**
- **Dataset** — Scraped from books.toscrape.com (1,000+ records)

## Project Workflow

### Task 1: Web Scraping
- Scraped 50 pages of book data using BeautifulSoup and Requests
- Collected title, price, star rating, and availability for each book
- Saved raw data to `books_raw.csv`

### Task 2: Data Cleaning & Preprocessing
- Removed currency symbol from price column and converted to float
- Mapped text ratings (One to Five) to numeric values (1 to 5)
- Standardized column names and stripped extra whitespace
- Saved cleaned data to `books_cleaned.csv`

### Task 3: Exploratory Data Analysis
- Analyzed distribution of book prices and ratings
- Calculated average price per rating category
- Identified price ranges with the highest-rated books
- Examined availability patterns across rating categories

### Task 4: Visualization & Dashboard
- Built charts using Matplotlib and Seaborn for price and rating distributions
- Created an interactive Power BI dashboard to track pricing trends and rating correlations

## Key Findings

| Finding | Detail |
|---------|--------|
| Price Distribution | Most books are priced between £10 and £30 |
| Top Rated | 5-star books are spread across all price ranges |
| Availability | Most books are in stock regardless of rating |
| Dashboard | Interactive filters for price range and rating category |

## Visualizations
- Histogram: Distribution of book prices
- Bar chart: Average price per rating category
- Count plot: Rating frequency distribution
- Power BI: Interactive pricing and rating dashboard

## Project Structure
Books-Price-Rating-Analysis/
│
├── book_scraper.ipynb            # Web scraping script
├── data_cleaning_models.ipynb    # Data cleaning and EDA
├── books_raw.csv                 # Raw scraped data
├── books_cleaned.csv             # Cleaned dataset
└── books_dashboard.pbix          # Power BI dashboard

## How to Run
1. Clone the repository
2. Open `book_scraper.ipynb` and run to scrape fresh data
3. Open `data_cleaning_models.ipynb` for cleaning and EDA
4. Install required libraries: `pip install pandas matplotlib seaborn beautifulsoup4 requests`
5. Run all cells in order

## Author
**Shalini Jakkam**
- LinkedIn: https://www.linkedin.com/in/shalini-jakkam-815046308/
- GitHub: https://github.com/Shalinijakkam
