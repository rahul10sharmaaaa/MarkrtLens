MarketLens
A modern web application for viewing and comparing stock prices using real-time data from Alpha Vantage API.

Features
Real-time stock price visualization with interactive charts
Multiple stock comparison on a single chart
Flexible time ranges: 1 week, 1 month, 6 months
Responsive design optimized for all devices
Professional error handling
Quick Start
Clone the repository

git clone <repository-url>
cd MarketLens
Set up virtual environment

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

pip install -r requirements.txt
Configure environment

Create a .env file in the root directory
Add your configuration:
ALPHA_VANTAGE_API_KEY=your_api_key_here
ALPHA_VANTAGE_BASE_URL=https://www.alphavantage.co/query
PORT=5000
Run the application

python3 app.py
Access the application Open your browser and navigate to http://localhost:5000

API Key Setup
Visit Alpha Vantage
Sign up for a free account
Generate your API key
Add the key to your .env file
Project Structure
MarketLens/
├── app.py                 # Flask backend
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables
├── templates/
│   └── index.html        # Main HTML template
└── static/
    ├── styles.css        # CSS styles
    └── script.js         # Frontend JavaScript
Technology Stack
Backend: Python Flask
Frontend: HTML5, CSS3, JavaScript
Charts: Chart.js
API: Alpha Vantage
Styling: Custom CSS with modern design principles
License
This project is open source and available under the MIT License.
