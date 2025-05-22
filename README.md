# Google-Play-Store-Data-Analysis-Feature-Engineering

📌 Project Overview
With over 2.5 million apps on the Google Play Store, understanding app trends, user behavior, and performance metrics has become crucial for developers, analysts, and businesses. This project focuses on performing Exploratory Data Analysis (EDA) and Feature Engineering on a dataset containing over 10,000 Android apps to uncover insights such as:

🔍 Most popular app categories

📥 App with the largest number of installs

📦 App with the largest size

⭐ Distribution of ratings, reviews, price, and content ratings

🧾 Dataset Information
Source: Google Play Store dataset

Rows: 10,841

Columns: 20

File format: CSV

📄 Key Features in the Dataset
Column Name	Description
App	Name of the app
Category	Category under which the app falls
Rating	App's rating on the Play Store
Reviews	Number of reviews
Size	Size of the app
Installs	Number of installs
Type	Free or Paid
Price	Price of the app
Content Rating	Age group suitability
Genres	Genre under which the app falls
Last Updated	Last updated date
Current Ver	Current version
Android Ver	Required Android version

✅ Steps Followed
1. 📦 Data Cleaning
Handled missing values

Removed duplicates

Converted data types (e.g., Size, Installs, Reviews with suffixes like M, K)

Removed special characters and standardized formats

2. 📊 Exploratory Data Analysis (EDA)
Distribution of Ratings

Top Categories by number of apps

Most installed apps

Relationship between Rating and Reviews

Free vs Paid app comparison

Price distribution of Paid apps

3. 🛠 Feature Engineering
Converted text-based metrics (Size, Installs, Reviews) to numeric values

Extracted update year from Last Updated

Created new features for price buckets, size bins, etc.

📷 Sample Visualizations
Bar plots for Category distribution

Pie chart for Content Rating

Scatter plot: Reviews vs Rating

Histogram: Price of Paid Apps

Heatmap of correlations between numeric features

📁 Repository Structure
bash
Copy
Edit
├── GooglePlayStore_EDA.ipynb       # Jupyter notebook with full analysis
├── googleplaystore.csv             # Dataset file
├── README.md                       # Project readme
├── requirements.txt                # Python dependencies (optional)
🧰 Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly (optional)

Jupyter Notebook
