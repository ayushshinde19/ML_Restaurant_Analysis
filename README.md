# Restaurant Data Analysis and Machine Learning Tasks

This repository contains a Jupyter Notebook https://github.com/ayushshinde19/ML_Restaurant_Analysis/blob/main/Restaurant_Analysis_Notebook.ipynb that performs various data analysis and machine learning tasks on a restaurant dataset.

The tasks covered are:
1.  **Predict Restaurant Ratings:** Building a regression model to predict restaurant ratings based on features like cuisine, location, price range, and votes.
2.  **Restaurant Recommendation:** Demonstrating simple content-based and popularity-based recommendation systems.
3.  **Cuisine Classification:** Classifying the primary cuisine of a restaurant based on its name and location.
4.  **Location-based Analysis:** Exploring geographical patterns, clustering restaurants by location, and analyzing metrics like density and average ratings in different areas.

## Dataset

The analysis uses the https://github.com/ayushshinde19/ML_Restaurant_Analysis/blob/main/Dataset%20.csv file included in this repository. This dataset contains information about various restaurants, including name, location, cuisines, rating, votes, etc.

## Repository Structure
├── Dataset .csv
├── Restaurant_Analysis_Notebook.ipynb
├── README.md
├── requirements.txt
└── gitignore
## Setup

1.  Clone the repository:
    ```bash
    git clone https://github.com/ayushshinde19/ML_Restaurant_Analysis/blob/main/Restaurant_Analysis_Notebook.ipynb
    cd ML_Restaurant_Analysis
    ```

2.  Create a virtual environment (recommended):
    ```bash
    python -m venv venv
    ```

3.  Activate the virtual environment:
    On Windows:
        ```bash
        venv\Scripts\activate
        ```
    On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

4.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5.  Ensure the dataset is in the correct location:
    Place the https://github.com/ayushshinde19/ML_Restaurant_Analysis/blob/main/Dataset%20.csv file in the root directory of the repository.

## How to Run the Code

1.  Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2.  Open the notebook:
    Your web browser should open. Navigate to and open the `Restaurant_Analysis_Notebook.ipynb` file.

3.  Run the cells:
    Execute the notebook cells sequentially from top to bottom. The notebook includes markdown explanations for each task.

## Results

The notebook will output results directly in the cells, including:
* Data exploration summaries and visualizations.
* Model evaluation metrics (MSE, RMSE, R2 for regression; Accuracy, Classification Report for classification).
* Recommendation lists.
* Location cluster analysis and plots.
* Interactive map saved as `restaurant_location_analysis_map.html` (open this file in your web browser).
* City-based analysis and plots.

## Contributing

Feel free to fork this repository and contribute!
