# Historic-Stocks-Revenue-Data-Analyse
# GameStop Stock and Revenue Analysis

This project analyzes the stock price and revenue data of GameStop (GME) using Python. The goal is to explore the relationship between stock prices and revenue over time, visualizing the data and extracting meaningful insights.

## Project Overview

In this project, we:
1. Downloaded and cleaned the stock and revenue data for GameStop.
2. Used web scraping techniques to fetch the latest revenue data.
3. Combined the stock data and revenue data into a single analysis.
4. Visualized the stock price and revenue using line plots.
5. Filtered the data to display results up to June 2021.

### Key Features
- **Web Scraping**: Extract GameStop's revenue data from a webpage.
- **Data Cleaning**: Remove unwanted characters like commas and dollar signs from the revenue data.
- **Data Analysis**: Analyze and visualize the relationship between stock prices and revenues.
- **Matplotlib Visualization**: Create graphs that plot stock prices and revenues over time.

## Installation

To run this project on your local machine, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Pip (Python's package installer)

### Install Dependencies

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/gamestop-stock-revenue-analysis.git
Navigate to the project directory:

bash
Copy code
cd gamestop-stock-revenue-analysis
Create a virtual environment (optional but recommended):

bash
Copy code
python3 -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Dependencies
This project uses the following Python libraries:

requests - for web scraping and downloading data.
beautifulsoup4 - for parsing HTML data.
pandas - for data manipulation.
matplotlib - for plotting and visualizing data.
You can install them with:

bash
Copy code
pip install requests beautifulsoup4 pandas matplotlib
Usage
Once the dependencies are installed, you can run the analysis and generate the plots.

Download the data and clean it.
Visualize the stock price and revenue over time by running:
bash
Copy code
python analyze_stock_revenue.py
This will generate a plot showing GameStop's stock price and revenue over time.

Contributing
Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request with your improvements.

Steps for contributing:
Fork the repository.
Clone your fork to your local machine.
Create a new branch for your changes.
Make your changes and commit them.
Push your changes to your fork.
Open a pull request to the main repository.
