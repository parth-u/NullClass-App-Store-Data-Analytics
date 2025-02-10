📊 Play Store Data Analysis Dashboard

🚀 Welcome to the Play Store Data Analysis Dashboard! This project visualizes key insights from Play Store app data using interactive charts and graphs. The dashboard is built with Dash, Plotly, and Python, featuring time-based visibility for different analyses. 🕒

📌 Features & Analyses

1️⃣ Revenue vs. Installs (Scatter Plot)

🎯 Objective: Visualize the relationship between revenue and the number of installs for paid apps only.
📈 Trendline: Shows correlation between revenue and installs.
🎨 Color-coded: Points are categorized based on app categories.

2️⃣ Ratings & Reviews per Category (Grouped Bar Chart) ⏳ Available from 3PM to 5PM IST

📊 Comparison of Average Rating & Total Reviews for the Top 10 categories by installs.
🚫 Filters applied:

Exclude categories with an average rating below 4.0.

Exclude apps with size below 10 MB.

Only include apps last updated in January.

3️⃣ Global Installs by Category (Choropleth Map) ⏳ Available from 6PM to 8PM IST

🌍 Visualizing global installs for the Top 5 app categories.
⚡ Highlight: Categories with more than 1 million installs.
🚫 Exclusions: Categories starting with "A", "C", "G", and "S".

4️⃣ Install Trends Over Time (Time Series) ⏳ Available from 6PM to 9PM IST

📈 Track install trends over time, segmented by category.
🔥 Highlight: Periods of 20%+ month-over-month growth.
🎯 Filters applied:

Content Rating: Teen

App Name: Starts with "E"

Installs: More than 10,000

5️⃣ Correlation Matrix (Heatmap) ⏳ Available from 2PM to 4PM IST

🔥 Shows correlation between Installs, Ratings, and Reviews.
🔎 Filters applied:

Only apps updated within the last year.

Minimum 100,000 installs.

Minimum 1,000 reviews.

Genres excluded: Starting with "A", "F", "E", "G", "I", "K".

📊 Interactive Dashboard

✨ Built with Dash & Plotly.
📅 Time-based visibility: Different analyses are shown based on the time of day.
📥 Download option: Save the dashboard as an HTML file.

🛠 Installation & Setup

# Clone the repository
git clone https://github.com/parth-u/NullClass-App-Store-Data-Analytics.git
cd playstore-dashboard

# Install required dependencies
pip install -r requirements.txt

# Run the dashboard
python app.py


