Airline Analytics Dashboard - Power BI

Overview
This repository contains an interactive Airlines Analytics Dashboard built using Microsoft Power BI. The dashboard analyzes flight booking data across various airlines and cities in India, providing comprehensive insights into flight patterns, pricing trends, and travel analytics.

 📊 Dashboard Features
- **Interactive KPI Cards**: Total flights (300.1K), average price ($20.8K), and average duration (733.3 mins)
- **Multi-dimensional Filtering**: Filter by airline, destination city, class (Business/Economy), and days left
- **Flight Distribution Analysis**: Visual breakdown by airline, source/destination cities, and arrival times
- **Price Analytics**: Price comparison by arrival time and departure time with flight count correlation
- **Source City Heatmap**: Interactive visualization showing flight origins (Chennai, Mumbai, Kolkata, Bangalore)
- **Time-based Analysis**: Flight patterns by departure and arrival time slots

## 🛠️ Technologies Used
- **Microsoft Power BI Desktop** - Primary visualization tool
- **Power Query** - Data transformation and cleaning
- **DAX (Data Analysis Expressions)** - Custom calculations and measures
- **Power BI Service** - Publishing and sharing dashboards

```

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version)
- Access to the data source (if connecting to live data)

### Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. Open Power BI Desktop

3. Open the `.pbix` file.

4. Refresh the data connections if needed

5. Explore the interactive dashboard!

## 📈 Key Insights
- **Vistara leads in flight volume** with the highest number of flights among all airlines
- **Evening flights are most expensive** showing peak pricing during high-demand time slots
- **Night flights have highest frequency** indicating popular overnight travel preferences
- **Mumbai and Delhi dominate** as primary source cities for domestic travel
- **Price varies significantly by departure time** with morning flights offering better value
- **Average flight duration** of over 12 hours suggests long-haul domestic routes

## 🖼️ Dashboard Preview
![Dashboard Overview]<img width="1500" height="805" alt="Airline Analytics Dashboard" src="https://github.com/user-attachments/assets/ff4dfbcc-1c4d-4fa1-a090-ef6042e797d4" />


*Main dashboard showing key metrics and visualizations*

## 📊 Dataset Information
- **Source**: Scraped from a famous flight booking website
- **Scope**: Domestic flights between major Indian cities
- **Records**: 300,000+ flight booking records
- **Time Period**: Date-wise structured flight data
- **Update Frequency**: Static dataset for analysis purposes

### Dataset Features (11 columns):
1. **Airline** - 6 different airline companies (Vistara, Air India, Indigo, GO_FIRST, AirAsia, SpiceJet)
2. **Flight** - Unique flight codes for each route
3. **Source City** - 6 major departure cities (Delhi, Mumbai, Bangalore, Kolkata, Hyderabad, Chennai)
4. **Departure Time** - Categorized time periods (Morning, Early_Morning, Evening, Night, Afternoon, Late_Night)
5. **Stops** - Number of stops between source and destination (3 distinct values)
6. **Arrival Time** - Categorized arrival time periods (6 time labels)
7. **Destination City** - 6 major arrival cities matching source cities
8. **Class** - Seat class (Business, Economy)
9. **Duration** - Flight duration in hours (continuous variable)
10. **Days Left** - Days between booking date and travel date
11. **Price** - Ticket price (target variable for analysis)

## 🔧 Customization
The dashboard can be customized by:
- Modifying filters and slicers
- Adding new visualizations
- Updating data connections
- Creating additional calculated measures

## 📝 Dashboard Usage Instructions
1. **Filter by Airlines**: Use the airline dropdown to focus on specific carriers (Vistara, Air India, etc.)
2. **Select Destinations**: Choose specific destination cities using the dropdown filter
3. **Class Selection**: Toggle between Business and Economy class using checkboxes
4. **Days Left Slider**: Adjust the range slider (1-49 days) to see how advance booking affects pricing
5. **Interactive Charts**: Click on any bar or chart element to cross-filter all other visualizations
6. **Source City Heatmap**: Click on city tiles (Chennai, Mumbai, Kolkata, Bangalore) to filter by origin
7. **Time Analysis**: Explore flight patterns by clicking on different time periods in the arrival/departure charts

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Open

## 📧 Contact
Email -  sasahemakumara@gmail.com

Project Link: [https://github.com/yourusername/your-repo-name](https://github.com/SASAXE/Airline-Analytics-Dashboard)

## 🙏 Acknowledgments
- Flight booking website for providing the comprehensive dataset
- Indian aviation industry data for enabling domestic travel analysis
- Power BI community for dashboard design inspiration
- Open-source data contributors in the aviation analytics space

---
*This Airlines Analytics Dashboard was created to provide actionable insights for travelers, airlines, and aviation industry stakeholders to make informed decisions based on flight patterns and pricing trends.*
