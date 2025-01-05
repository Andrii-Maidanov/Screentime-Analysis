# Screentime Analysis

This project analyzes the usage patterns of different apps over time, providing insights into app usage duration, the number of notifications received, and the frequency of app openings. The analysis is visualized using Tableau, showcasing various aspects of app usage for better understanding and decision-making.

## Files

### screentime_analysis.csv

This CSV file contains the raw data used for the analysis. The dataset includes the following columns:
- **Date**: The date of the screentime activity.
- **App**: The name of the app used.
- **Usage (minutes)**: The total minutes the app was used on that date.
- **Notifications**: The number of notifications received from the app on that date.
- **Times Opened**: The number of times the app was opened on that date.

### screentime_dashboard.png

This image file shows a Tableau dashboard with the following visualizations:
- **Opened times vs App**: A heatmap showing how many times each app was opened on specific dates.
- **Total minutes per App**: A bar chart displaying the total usage time in minutes for each app.
- **Total times Opened per App**: A bar chart illustrating how many times each app was opened overall.
- **App Notifications**: A line chart showing the number of notifications received for each app over time.

## Usage

1. Load the `screentime_analysis.csv` dataset to perform further analysis or to visualize the data in your preferred tool.
2. Use the `screentime_dashboard.png` for a quick overview of the app usage trends and insights.

## Insights

- Identify which apps are used the most based on total usage time and frequency of openings.
- Track how notifications might influence the frequency of app openings.
- Analyze trends in app usage over time to understand user behavior.

## Tools Used

- **Tableau**: For creating visualizations and dashboards.
- **Pandas**: For data manipulation and analysis (if further analysis is needed).

## Author

- Andrii Maidanov
