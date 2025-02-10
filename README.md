The goal of this project was to *scrape product data* (name, price, rating, and description) from Snapdeal, clean and store the data in *SQLite, and build a **Django web interface* to display the scraped data.

---

## ✅ Progress (60% Completed)
### *1. Web Scraping with BeautifulSoup*
- Implemented a Python script using requests and BeautifulSoup to scrape product details.
- Extracted *name, price, rating, and description* from Snapdeal.
- Saved the data into a *CSV file* (snapdeal_mobiles.csv).

### *2. Data Cleaning & Storage*
- Processed the scraped data using *Pandas*.
- Converted price values into numeric format for better processing.
- Handled missing data (e.g., missing ratings or descriptions).
- Planned to store cleaned data into *SQLite*, but this step is pending.

### *3. Django Web Interface (In Progress)*
- Set up a Django project and created a basic app.
- Configured models.py for storing product data.
- Created basic views.py and templates for displaying product data.
- *Pending:* Connecting SQLite database and completing UI design.

---

### *1. Clone the Repository*
``` bash
git clone https://github.com/your-username/ecommerce-scraper.git
cd ecommerce-scraper
**### *2. Set Up Virtual Environment & Install Dependencies
``` bash
Copy
Edit
python -m venv env
source env/bin/activate  # For Mac/Linux
env\Scripts\activate  # For Windows

pip install -r requirements.txt**

3. Run Django Server
bash
Copy
Edit
python manage.py runserver
Open http://127.0.0.1:8000/ in your browser to see the web interface.

E-Commerce Website will look like this - http://api.scraperapi.com/?api_key=3cb5771e4423831db65f1c21c043c237&url=https://www.ebay.com/sch/i.html?_nkw=laptops
