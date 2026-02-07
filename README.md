NHL Stats – End-to-End Data Pipeline (Scraping → Cleaning → Analysis → Insights)

This project demonstrates a complete data workflow for NHL player statistics — from automated data collection to analytical insights.
It is designed as a practical showcase of real-world data handling, including web scraping, data processing, exploratory analysis, and the generation of business-oriented recommendations.

The entire pipeline is reproducible via Jupyter notebooks.

📌 Project Objectives
```text
Automatically download raw HTML data from selected NHL statistics pages.

Parse, clean, and transform the data into structured datasets.

Analyze statistical patterns and team performance indicators.

Deliver interpretable insights and recommendations based on the results.
```
📂 Project Structure
```text
NHL_stats/
|
|-- data/
|   |-- raw/          # original scraped HTML samples
|   |-- interim/      # intermediate JSON outputs
|   `-- processed/    # final cleaned CSV datasets
|
|-- drivers/          # chromedriver / webdriver (not included in repo)
|
|-- notebooks/        # Jupyter notebooks (download, cleaning, analysis, business insights)
|
|-- requirements.txt
`-- README.md
```
🚀 How to Run the Project
1. Clone the repository.

2. Install dependencies
pip install -r requirements.txt

3. Install the appropriate browser driver

This project uses Selenium for automated data collection.
You can use any supported browser, as long as you install the correct driver:

Browser	Driver	Link
Chrome	ChromeDriver	https://chromedriver.chromium.org/downloads

Firefox	GeckoDriver	https://github.com/mozilla/geckodriver/releases

Edge	EdgeDriver	https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/

Download the driver matching your browser version.

Place the executable inside the drivers/ folder.

4. Run the notebooks in order

01_DataDownload.ipynb – automated scraping

02_DataProcessing.ipynb – parsing & cleaning

03_DataAnalysis.ipynb – exploration & statistical analysis

04_BusinessRecommendations.ipynb – insights & interpretation

🛠️ Technologies Used
```text
Python

pandas

numpy

matplotlib

BeautifulSoup4

Selenium

Requests

Jupyter Notebook

HTML + JSON + CSV data formats
```

📈 What This Project Demonstrates

✔ Practical experience with web scraping
✔ End-to-end ETL pipeline design
✔ Data cleaning and transformation
✔ Exploratory data analysis
✔ Communication of insights and findings
✔ Clean project structure and reproducibility
