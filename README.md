# Team_Utopia_Interactive-CO2-Emission-Dashboard
CO2 Emissions Dashboard
This project is a web-based interactive dashboard that allows users to explore CO2 emissions by country and sector. Built using Dash (a Python framework for building web applications), the dashboard visualizes CO2 emissions data and enables users to filter the data based on country selection.

The data includes CO2 emissions for multiple countries in different sectors such as "Energy" and "Transport". The user can select a country from a dropdown menu and view a bar chart displaying the CO2 emissions by sector for that country.

Features:-
1. Dropdown Selection: Users can select a country to filter the data and see the CO2 emissions for that country.
2. Bar Chart Visualization: A bar chart is displayed to visualize CO2 emissions by sector for the selected country.
3. Dynamic Updates: The graph updates dynamically based on the selected country.
   
Technologies Used:-
Dash: A Python framework for building web applications.
Plotly: A graphing library for creating interactive visualizations.
Pandas: A data manipulation and analysis library in Python.

Requirements:-
To run this project, you need to install the following Python libraries:
pip install dash plotly pandas

Running the App
Clone or download the project repository.
Make sure you have all the required libraries installed by running the following command in your terminal:

Run the Python script app.py to start the Dash app:
python app.py

How to Use the Dashboard
1. Select a Country: Use the dropdown menu at the top of the page to select a country.
2. View the Graph: The bar chart will update to display CO2 emissions for the selected country, broken down by sector (Energy, Transport, etc.).
3. Explore Data: You can compare CO2 emissions across different sectors for any given country.

Example Data
The current data includes CO2 emissions for the following countries:

USA
China
India
Germany
UK
Each country has data for two sectors: "Energy" and "Transport".

Project Structure:-
.
├── app.py                # Main application code
└── README.md             # This file

Acknowledgments:-
1. Dash and Plotly for providing the powerful frameworks for building interactive web applications and visualizations.
2. Pandas for providing efficient data structures and analysis tools.

