## Road Accident Data Analysis and Prediction

This project is an end-to-end data science endeavor focused on analyzing and predicting road accident trends in India using data from 2014 and 2016. The goal is to identify key factors influencing accidents and build a predictive model to assist in strategic planning and resource allocation for road safety.

-----

### Features

  * **Data Cleaning and Preprocessing:** Handles missing values and aggregates data to prepare it for analysis.
  * **Exploratory Data Analysis (EDA):** Analyzes the impact of different weather conditions and regions (states) on accident rates, fatalities, and injuries.
  * **Data Visualization:** Generates various plots, including correlation heatmaps and bar charts, to visually represent key insights.
  * **Predictive Modeling:** Develops a **Linear Regression** model to forecast total accidents and accident severity for 2016 based on 2014 data.
  * **Results:** Evaluates model performance using the R² score and visualizes predictions against actual values.

-----

### Technologies Used

  * **Python:** The core programming language for the project.
  * **Pandas:** Used for data manipulation and analysis.
  * **NumPy:** Utilized for numerical operations.
  * **Matplotlib & Seaborn:** Libraries for creating static, interactive, and animated visualizations.
  * **Scikit-learn:** A machine learning library used for building the predictive models.

-----

### How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```
2.  **Ensure you have the required data file:**
    Place the `Acc_Classified_according_to_Type_of_Weather_Condition_2014_and_2016.csv` file in the project's root directory.
3.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4.  **Execute the Script:**
    ```bash
    python your_project_script_name.py
    ```

-----

### Output

Running the script will produce several outputs:

  * Multiple plots displayed, including correlation heatmaps and bar charts comparing 2014 and 2016 data.
  * R² scores for both the accident and severity prediction models printed to the console.
  * A new CSV file named `project.csv` will be created, containing the aggregated and cleaned data.
