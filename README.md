# web-scrapper-using-BeautifulSoap
# 🧠 CodeChef Profile Scraper

A lightweight Python script that scrapes and displays public information from any **CodeChef user profile** using `BeautifulSoup` and `requests`.

## 📌 Features

- Retrieves **Username**, **Country**, **Profession**
- Shows **Current Rating**, **Highest Rating**, and **Global Rank**
- Counts of **Fully and Partially Solved Problems** (Practice & Others)
- Grabs the **User's Avatar Image URL**
- Fast and easy to run in any Python environment (no browser automation)

---

## 📁 Project Structure
codechef-profile-scraper/
│
├── main.py # Main scraping script
└── README.md # Project documentation
---

## 🧰 Requirements

- Python 3.x
- Libraries:
   `requests`
  - `beautifulsoup4`
  - `lxml`
Install them via pip:
bash
pip install requests beautifulsoup4 lxml

git clone https://github.com/your-username/codechef-profile-scraper.git
cd codechef-profile-scraper
Run the script:

bash

python codechef_scraper.py
Enter a CodeChef username when prompted:
Enter username: <your_codechef_username>

✅ Get details like:

Username: shreeyash   Global Rank: 1203
Location: India
Profession/Student: Student
Highest Rating: 1887
Avatar URL: https://cdn.codechef.com/sites/default/files/uploads/pictures/...
Fully solved Problems - 32 Practice Problems and 12 Other Problems
Partially solved Problems - 4 Practice Problems and 5 Other Proble
📄 License
This project is open-sourced under the MIT License.

🙏 Acknowledgements
BeautifulSoup
CodeChef
Created with ❤️ by Shree
