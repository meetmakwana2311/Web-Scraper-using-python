# 🌐  Web Scraper using Python

A modular Python-based web scraping tool that uses **BeautifulSoup** and **requests** to extract structured data from various types of websites. This project showcases how to implement targeted scrapers for popular platforms like GeeksforGeeks, Stack Overflow, GitHub, and general news sites.

---

## 📌 Features

- 🔍 **GeeksforGeeks**: Extracts title, article content, code snippets, and related articles.
- 🧠 **Stack Overflow**: Fetches latest questions with tags, stats, excerpts, and URLs.
- 💻 **GitHub**: Scrapes repository name, description, languages, stars/forks, files, and recent commits.
- 📰 **News Websites**: Collects top headlines and related article links using generic selectors.
- 📄 **JSON Export**: Saves structured scraped data to `multi_website_scraping_results.json`.

---

## 🛠️ Technologies Used

- Python 3.x
- `requests`
- `beautifulsoup4`
- `json`
- `time`
- `urllib.parse`
- `re`

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/web-scraper.git
cd web-scraper
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```
OR 

```bash
pip install beautifulsoup4 requests
```

### 3. Run the script

```bash
python web_scraper.py
```

---

## 📁 Output

* Scraped data will be saved in:

  * `multi_website_scraping_results.json` — neatly formatted with URL, title, content, and metadata.

---

## 🧪 Example Use Cases

* Educational demos for web scraping
* Data collection for machine learning or research
* Personal portfolio projects
* Initial scaffolding for automation scripts

---

## 📸 Screenshots
![1](https://github.com/user-attachments/assets/d9ff77b3-1e91-4f78-a22a-7a2886b7c617)

![2](https://github.com/user-attachments/assets/ae0c15f2-4213-46cb-b36f-996fe885ce45)

![image](https://github.com/user-attachments/assets/7f2c3fbc-cba3-4faa-8ebd-967f4d7d841c)


---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, improve scraping logic for more sites, or refactor the code into smaller components.

---

## ⚠️ Disclaimer

This tool is meant for educational and personal use. Always check and respect a website’s `robots.txt` and terms of service before scraping. Avoid overloading servers.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.


