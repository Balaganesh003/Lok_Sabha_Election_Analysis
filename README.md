# Lok Sabha Indian Election 2024 Data Analysis

This project scrapes and analyzes data from the Election Commission of India (ECI) website for the June 2024 General Elections. It provides various insights and visualizations about the election results.

## Features

- Scrapes election data from the ECI website
- Generates multiple insights about the election results
- Creates visualizations for easy understanding of the data
- Saves insights to a text file and visualizations as PNG images

## Requirements

- Python 3.x
- Libraries: requests, BeautifulSoup4, pandas, matplotlib

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Balaganesh003/Lok_Sabha_Election_Analysis_Kalvium_task.git
   cd Lok_Sabha_Election_Analysis_Kalvium_task


2. Install the required libraries: 
   ```sh
   pip install requests bs4 pandas matplotlib

## Usage

Run the main script: `python main.py`

This will scrape the data, generate insights, and create visualizations.

## Generated Insights

The script generates the following insights:

1. Election closeness
2. Government formation analysis
3. Overall election statistics
4. Party size distribution
5. Potential kingmakers
6. Independent candidates performance
7. Top 5 candidates by votes
8. Top 5 candidates by votes for top 10 parties
9. Bottom 5 candidates by votes
10. Bottom 5 candidates by votes for top 10 parties

## Output

- `election_insights.txt`: Contains all the generated insights
- Various PNG files: Visualizations for different analyses

## Notes

- This script respects the website's robots.txt and includes a user-agent header.
- The data is scraped from a specific URL. If the website structure changes, the scraping functions may need to be updated.
- Some insights depend on the availability of candidate-specific data.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/indian-election-analysis/issues) if you want to contribute.
