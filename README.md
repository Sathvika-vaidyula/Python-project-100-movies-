# Python-project-100-movies-
# 🎬 Top 100 Movies Scraper

This Python script scrapes the **Top 100 Movies of All Time** from an archived version of Empire Online's website and saves them in reverse order (from #1 to #100) into a file named `movies.txt`.

---

### 📌 Features
- Sends a request to an archived webpage.
- Parses the HTML using BeautifulSoup.
- Extracts movie titles from `<h3>` tags with class `title`.
- Reverses the list to start from the top-ranked movie.
- Saves the titles to a `.txt` file.

---

### 📂 Output
Creates a `movies.txt` file containing one movie per line like:

