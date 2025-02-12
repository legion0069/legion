Traffic Analysis Dashboard
Overview
This project is a web-based Traffic Analysis Dashboard built using Dash, Plotly, and Pandas. The dashboard allows users to analyze traffic data and view insights based on traffic counts, vehicle distribution, and traffic conditions over a selected date and time. The application provides interactive visualizations, including pie charts, bar charts, and line graphs, to facilitate decision-making for users in different traffic situations.

Features
Date and Time Selection: Choose a date and time to analyze traffic data.
Traffic Data Filters: Filter data by date, time, and road to get precise traffic insights.
Visualization:
Pie Chart: Displays vehicle distribution (Car, Bike, Bus, Truck) for the selected time.
Weekly Bar Chart: Shows traffic count over the course of the week for the selected date.
Weekday Line Chart: Displays traffic count across different weekdays.
Traffic Prediction: Provides an analysis of the traffic count and suggests alternative routes or times based on traffic conditions.
Traffic Status: Shows the current traffic status (Normal, Heavy, Light) for the selected time.
Requirements
Python 3.7+
Libraries:
Dash
Plotly
Pandas
To install the required libraries, use the following command:

bash
Copy
Edit
pip install dash plotly pandas
Setup
Clone or download the repository.
Ensure you have the required CSV file (filtered_output_updated.csv) with the relevant traffic data.
Update the path of the CSV file in the script to point to the correct location:
python
Copy
Edit
df = pd.read_csv("C:/Users/veruk/Documents/filtered_output_updated.csv")
Run the application:
bash
Copy
Edit
python app.py
The app will start a local development server at http://127.0.0.1:8050/.

Usage
Open the dashboard in your browser.
Select a date using the Date Picker.
Choose a time from the Time Dropdown.
Select a road from the Road Dropdown.
Click Analyse to visualize the traffic data for the selected date and time.
Click Reset to clear the visualizations and inputs.
Example Screenshots
Traffic Distribution Pie Chart
Weekly Traffic Count Bar Chart
Weekday Traffic Line Chart
License
This project is licensed under the MIT License - see the LICENSE file for details.
