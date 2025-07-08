# Tweets Search & Download

A simple Python tool to search for tweets using specific keywords and download them into a CSV file. Powered by the `snscrape` library, this script makes it easy to gather public Twitter data for research, analysis, or archiving purposes.

## 🔍 Features

- Search tweets by keyword
- Set the number of tweets to retrieve
- Save results into a structured CSV file
- Collects tweet content, date, username, and more

## 🛠️ Requirements

- Python 3.6+
- `snscrape`
- `pandas`

Install dependencies:

```bash
pip install -r requirements.txt
🚀 Usage
Run the script using:

bash
Copy
Edit
python tweet_search_download.py
You will be prompted to enter:

The search keyword

The number of tweets to fetch

The output file name

Tweets will be saved to the specified CSV file.

📁 Output
The CSV file contains:

Date

Tweet content

Username

Tweet ID

URL

📌 Notes
This tool uses snscrape, which does not require Twitter API keys.

Only publicly available tweets are fetched.

📄 License
This project is open-source and available under the MIT License.

yaml
Copy
Edit

---

Let me know if you'd like a version with screenshots, example outputs, or badges!
