A comprehensive Python-based system for collecting, analyzing, and managing travel data from multiple sources for academic research purposes.

## 🎯 Features
- **Hotel Data Collection**: Scrapes and generates hotel information (Booking.com style)
- **Flight Data Collection**: Collects flight schedules, prices, and availability
- **Travel Recommendations**: Generates personalized travel suggestions
- **Data Export**: Saves data in CSV, Excel, and JSON formats
- **Multi-source Integration**: Combines data from various public APIs

## 🛠️ Technologies Used
- **Python 3.9+**
- **Pandas** - Data analysis and manipulation
- **Requests** - HTTP requests for API integration
- **Faker** - Mock data generation
- **Python-dotenv** - Environment variable management

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/bushra95256-cmyk/travel-scraper.git
cd travel-scraper
pip install pandas requests python-dotenv faker
pip install -r requirements.txt
python travel_data_scraper.py
travel-scraper/
├── travel_data_scraper.py    # Main application code
├── requirements.txt          # Python dependencies
├── README.md                # This documentation file
├── .gitignore               # Git ignore rules
├── LICENSE                  # MIT License file
├── hotels.csv               # Generated hotel data
├── flights.csv              # Generated flight data
└── recommendations.csv      # Travel recommendations
# Run the main scraper
python travel_data_scraper.py

# Output files will be created:
# - hotels.csv
# - flights.csv 
# - recommendations.csv
# hotels.csv
id,name,city,price,rating
1,Grand Dubai Hotel,Dubai,450,4.5
2,Royal London Hotel,London,380,4.2
3,Plaza Paris Hotel,Paris,420,4.7
# Add test files and run
python test_scraper.py
