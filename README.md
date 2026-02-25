# AI-powered-web-scraper-
An AI-powered web scraping agent that navigates web pages, extracts book data, filters books under £20, and stores results in structured CSV and JSON formats.
# 🤖 AI Web Scraping Agent

This project implements an **AI-powered information agent** that autonomously navigates a website, extracts specific data, applies filtering logic, and stores results in structured formats.

The agent demonstrates Artificial Intelligence concepts such as sensors, actuators, goal-based behavior, and interaction with a semi-structured web environment.

---

## 📌 Features

- Fetch webpage content using HTTP requests
- Parse HTML using BeautifulSoup
- Extract book title, price, and availability
- Filter books under £20
- Navigate multiple pages (pagination)
- Handle errors gracefully
- Save output in CSV and JSON format
- Ethical scraping with request delays

---

## 🧠 AI Concepts Demonstrated

- Intelligent Information Agent
- PEAS framework
- Goal-based agent behavior
- Sensors (HTML parsing)
- Actuators (HTTP requests)
- Semi-structured environment understanding
- Ethical data collection

---

## 🛠 Technologies Used

- Python
- Requests
- BeautifulSoup4
- Pandas
- Google Colab

---

## ⚙️ How It Works

1. Send HTTP request to the website
2. Receive HTML content
3. Parse HTML using BeautifulSoup
4. Identify book elements via CSS selectors
5. Extract title, price, and availability
6. Apply filtering condition (price < £20)
7. Store extracted data
8. Navigate to the next page
9. Save final results into CSV and JSON

---
## ⚙️ Install Dependencies 
pip install requests beautifulsoup4 pandas
## 🚀 Usage

Run the notebook or Python script to start scraping.

The agent will:

- Visit pages  
- Extract books  
- Filter data  
- Generate output files  

---

## 📊 Output Example

The generated dataset includes:

- Title  
- Price  
- Availability  

Saved as:

- CSV file  
- JSON file  

---

## ⚠️ Ethical Scraping

This project follows ethical scraping practices:

- Uses request delays  
- Handles errors  
- Respects website structure  
- Demonstrates robots.txt awareness  

---

## 🎯 Learning Outcomes

After completing this project, students understand:

- How AI agents interact with web environments  
- Data extraction from semi-structured sources  
- Pagination handling  
- Filtering logic  
- Structured data storage  

---

## 🔮 Future Improvements

- Selenium support for dynamic websites  
- Keyword-based scraping  
- Database storage  
- Parallel scraping  
- AI-based selector detection  
- Real-time dashboards  

---

## 👨‍💻 Author

**Muhammad Furqan**  
