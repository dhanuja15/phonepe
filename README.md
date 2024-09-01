# PhonePe Pulse Data Visualization and Exploration

## Project Overview

**PhonePe Pulse Data Visualization and Exploration** is a user-friendly tool built using Streamlit and Plotly. It provides interactive and insightful visualizations of data extracted from the PhonePe Pulse GitHub repository, making it an invaluable asset for data analysis and decision-making.

## Features

- Live geo visualization dashboard
- Interactive user interface with at least 10 dropdown options for data exploration
- Efficient data storage and retrieval using MySQL
- User-friendly and mobile-accessible design

## Technologies Used

- **GitHub Cloning**
- **Python**
- **Pandas**
- **MySQL**
- **mysql-connector-python**
- **Streamlit**
- **Plotly**

## Domain

**Fintech**

## Problem Statement

The PhonePe Pulse GitHub repository contains extensive metrics and statistics. The objective is to extract and process this data into actionable insights, presented through an interactive and user-friendly dashboard.

### Project Steps:

1. **Data Extraction**: Script-based cloning of the GitHub repository to fetch data in formats like CSV or JSON.
2. **Data Transformation**: Use Python and Pandas for data manipulation and pre-processing, addressing cleaning, missing values, and transformation needs.
3. **Database Insertion**: Utilizing `mysql-connector-python` to insert processed data into a MySQL database.
4. **Dashboard Creation**: Employ Streamlit and Plotly to create an engaging geo-visualization dashboard with multiple user-selectable options.
5. **Data Retrieval**: Fetch and display data dynamically from the MySQL database using Pandas.
6. **Deployment**: Ensure the solution is secure, efficient, and accessible to users online.

## Approach

Our approach harnesses Python's rich ecosystem for data handling and visualization, seamlessly integrating data extraction, transformation, storage, and visualization into a cohesive, interactive experience.

## Results

The project culminates in a live, interactive dashboard providing valuable insights and information from the PhonePe Pulse GitHub repository. It serves as a robust tool, supporting data-driven evaluations and insights.

## Installation Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/phonepe-pulse-viz.git
   cd phonepe-pulse-viz

2.**Install Required Packages:**
    bash
    pip install -r requirements.txt

3.**Set Up the Database:**

   Ensure MySQL is running and accessible.
   Run the SQL scripts provided in the sql directory to set up the necessary schema and tables.

4.**Run the Application:**
   bash
   streamlit run app.py

5.**Usage**
  Access the dashboard via your web browser.
  Use dropdown menus and interactive controls to explore various metrics and insights.

6.**Dataset**
  Dataset Link: https://github.com/PhonePe/pulse#readme
  Inspired From: PhonePe Pulse

Contributions are welcome! Please open an issue to discuss your ideas, and feel free to submit pull requests.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contact**
For any questions or feedback, reach out to dhanuja1503@gmail.com.

Thank you for exploring PhonePe Pulse Data Visualization and Exploration. We hope this tool proves valuable for your analysis and insights needs!
 
