📊 Dash Dashboard Project
🚀 Overview

This project demonstrates a simple interactive dashboard using Dash in Python. The application displays both bar and line charts to visualize sample data on a web-based interface.
🛠️ Technologies Used

    Python
    Dash
    Dash Core Components (dcc)
    Dash HTML Components (html)

📁 Project Structure

    Dashboard.py – Main application file containing the Dash layout and logic.

📈 Features

    Dynamic Graphs: A combination of bar and line charts.
    Interactive Interface: Easy navigation with customizable axes titles.
    Simple Setup: Minimal configuration required for deployment.

⚙️ How to Run the Project

    Clone the Repository:

git clone <repository-url>
cd <project-folder>

Create a Virtual Environment (Optional but Recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install Dependencies:

pip install dash

Run the Application:

    python Dashboard.py

    Open in Browser:
    Visit http://127.0.0.1:8050/ to view the dashboard.

📝 Code Explanation

    Layout: A simple layout containing a header (html.H1) and a graph (dcc.Graph).
    Figure Data: Two datasets displayed in bar and line chart formats.
    Axes Titles: Custom titles for both x-axis and y-axis.
