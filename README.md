# Seattle Airbnb Data Visualization

## 📊 Project Overview
This Tableau project visualizes Airbnb listings across Seattle, WA. The goal is to provide a tool for travelers to find accommodation that fits their budget and preferred location. The dashboard moves beyond simple averages to show the distribution of individual listings.

## 🗂 Dataset
**Source:** Seattle Airbnb Open Data
**Key Fields Used:**
- `Latitude` & `Longitude`: For plotting exact locations.
- `Price`: The nightly cost of the listing.
- `City` / `Neighbourhood`: For geographic grouping.
- `ID`: Unique identifier for each listing.

## 🚀 Key Features
- **Disaggregated Map View:** Unlike standard maps that average data into a single point, this visualization "explodes" the data to show thousands of individual listing locations.
- **Price Heatmap:** Listings are colored by price, allowing users to instantly spot expensive vs. affordable areas.
- **Interactive Filtering:** Users can drill down by specific neighborhoods to analyze local pricing trends.

## 🛠 How It Was Built
1. **Symbol Map:** Created using Latitude and Longitude.
2. **Analysis Fix:** "Aggregate Measures" was disabled to reveal individual data points instead of a single average dot.
3. **Custom Formatting:** Adjusted transparency and borders to handle overlapping data points.

## 💡 How to Use
1. **Hover:** Hover over any dot to see specific details about that listing.
2. **Filter:** Use the filter panel to select specific parts of Seattle.
3. **Zoom:** Use the map tools to zoom into street-level details.
