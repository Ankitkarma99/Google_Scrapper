# **📸 Google Image Scraper (Flask + BeautifulSoup)**

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![Flask](https://img.shields.io/badge/Flask-Web_App-red)]()
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web_Scraping-green)]()
[![Requests](https://img.shields.io/badge/Requests-HTTP_Library-orange)]()
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-purple)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

---

## 📘 Overview

The **Google Image Scraper** is a Flask-based web application that allows users to search for images using Google Search and download them automatically.
The app fetches images from Google search results using **BeautifulSoup** and **requests**. Users can input any query, and the images are saved locally.

---

## 🚀 Features

* Search Google Images by query
* Automatically download images to a local folder
* Handles multiple images at once
* Uses **custom headers** to avoid blocking
* Logs errors in a log file

---

## 🛠 Tech Stack

* **Python 3.10+**
* **Flask** – Web framework
* **BeautifulSoup** – HTML parsing
* **Requests** – HTTP requests
* **MongoDB** (optional) – for storing metadata
* **Logging** – error handling

---

## 📁 Project Structure

```
📦 google-image-scraper
 ┣ 📜 app.py
 ┣ 📜 templates/
 ┃   ┣ 📄 base.html
 ┃   ┣ 📄 index.html
 ┃   ┗ 📄 result.html
 ┣ 📜 static/
 ┃   ┣ 📄 css/
 ┃       ┣ 📄 main.css
 ┃       ┗ 📄 style.css
 ┗ 📂 images/   # Downloaded images will be stored here
```

---

## 📥 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/google-image-scraper.git
cd google-image-scraper
```

### 2️⃣ Install Dependencies

```bash
pip install flask requests beautifulsoup4 pymongo
```

### 3️⃣ Run the Flask App

```bash
python app.py
```

* Open `http://127.0.0.1:5000` in your browser
* Enter a search query and click **Search**
* Images will be downloaded to the `images/` folder

---

## 📄 Usage

1. Enter a keyword in the search box.
2. Click **Search**.
3. The app scrapes images from Google and saves them locally.
4. View downloaded images in the `images/` directory.

---

## 📝 Notes

* Ensure you have a stable internet connection.
* Avoid sending too many requests in a short time to prevent Google from blocking your IP.
* This project is for educational purposes only.

---

## 🤝 Contribution

Pull requests are welcome! Improve features, UI, or add metadata storage in MongoDB.

---

## 📜 License

This project is licensed under **MIT License**.

---
