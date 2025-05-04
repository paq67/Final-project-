# 🔍 Job Skill Trend Analyzer (LinkedIn Scraper + Heatmap)

This project scrapes job listings from LinkedIn for a given role and location, analyzes the demand for specific technical skills, and visualizes the results using a heatmap of the top cities.

## 📌 Features

- Scrapes multiple pages of job listings for a chosen title and location
- Extracts job title, company, location, and full description
- Detects presence of predefined technical skills (e.g., Python, SQL, AWS)
- Aggregates skill mentions by city
- Visualizes the top 10 cities using a heatmap

## 🚀 Technologies Used

- `requests` – For HTTP GET requests to LinkedIn job pages
- `BeautifulSoup` (bs4) – For HTML parsing and scraping
- `pandas` – For tabular data processing
- `matplotlib` & `seaborn` – For visualization
- `re` – For regular expression-based text extraction

## 📊 Example Output

A heatmap showing frequency of skills like Python, SQL, AWS across top cities such as Toronto, New York, and San Francisco.

