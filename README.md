# Blinkit Sales Analysis Dashboard

This project analyzes Blinkit's sales data to gain insights into key performance indicators and trends. The dashboard provides a comprehensive overview of sales performance, item-specific metrics, and outlet-level analysis.

## Project Overview

The dashboard offers a user-friendly interface for exploring Blinkit's sales data. Key features include:

- **Total Sales and Average Sales:** Displays overall sales and average sales performance.
- **Total Items and Average Rating:** Shows the total items sold and the average rating.
- **Outlet Size and Location Analysis:** Breaks down sales by outlet size and location (Tier 1, Tier 2, Tier 3 cities).
- **Fat Content and Item Type Analysis:** Visualizes sales based on fat content (low fat, regular) and item type categories.
- **Outlet Type Comparison:**  Compares sales across different outlet types (Supermarket Type1, Grocery Store, etc.).
- **Data Filtering:** Interactive filter panels allow users to drill down into specific data segments.

## Data Transformation and Cleaning

The sales data underwent a cleaning and transformation process:

- **Handling Missing Values:** Missing values were assumed to be negligible and were dropped for simplicity.
- **Data Type Conversion:** Sales data was converted to numeric for calculations.
- **Feature Engineering:** No new features were engineered in this version.
- **Outlier Treatment:** Outliers were not explicitly handled in this initial version.

## Exploratory Data Analysis (EDA)

EDA was performed to understand data patterns and trends:

- **Descriptive Statistics:** Basic statistics (mean, median, etc.) were calculated for sales and ratings.
- **Data Visualization:** Bar charts, pie charts, and line graphs were used to visualize sales trends.
- **Correlation Analysis:** Correlation analysis was not performed in this version.

## Project Inspiration and Guidance

This project was inspired by and received guidance from the "Data Tutorials" YouTube channel. I extend my sincere gratitude to them for their valuable tutorials and support.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Streamlit

## Setup and Installation

1. Clone the repository: `git clone https://github.com/janviAnalysis/Projects.git`
2. **Set up the environment:**
   - Ensure you have Python 3.7 or higher installed.
   - Create a virtual environment (recommended): `python3 -m venv venv` (Windows: `python -m venv venv`)
   - Activate the environment: `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
   - Install dependencies: `pip install -r requirements.txt`  (Create `requirements.txt` with `pandas`, `matplotlib`, `seaborn`, `streamlit` inside).

## Usage

1. Navigate to the project directory: `cd Projects`
2. Run the dashboard: `streamlit run your_dashboard_script.py` (Replace `your_dashboard_script.py` with your actual script name)
3. Interact with the dashboard:
   - Use the filter panels on the left to select different criteria (outlet location, size, fat content, item type).
   - The charts will update dynamically based on your selections.
   - Explore the different visualizations to understand sales trends and key performance indicators.

## Contributions

Contributions are welcome! Please feel free to submit pull requests or open issues for any suggestions or improvements.

## Contact

Janvi Ambazhakan - https://www.linkedin.com/in/janvi-ambazhakan-950b39271?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bk%2FbgzG5FRRyeH0Rc8d9Zdw%3D%3D

