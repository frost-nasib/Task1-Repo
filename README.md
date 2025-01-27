# Biofuel Production Analysis By Arman Rashid
This project provides a Python program to analyze resource management in the catalytic conversion process for biofuel production. The program focuses on tracking resource utilization and calculating production efficiency using data from a CSV file.
## Key Features
##### 1. Data Import and Preprocessing:
Reads data from a user-provided CSV file.
Cleans data by handling missing values and ensuring numerical formatting.
Strips whitespace from column headers for consistent processing.
##### 2. Resource Utilization Calculation:
Computes the total resource usage (catalyst, energy, and raw materials) for each production run.
Calculates the biofuel yield for each run
##### 3. Efficiency Analysis:
Calculates resource efficiency as the ratio of biofuel yield to total resource input.
##### 4. Visualization:
Generates a bar chart comparing resource usage (catalyst, energy, raw materials) across production runs.
Creates a scatter plot showing the relationship between total resource usage and biofuel yield.
## How To Run
###### Install Dependencies:
Ensure you have Python installed along with the required libraries:

pip install pandas matplotlib

###### Run the Program:
Execute the script and provide the CSV file path when prompted:

python biofuel_analysis.py

###### Input Data:
The CSV file should contain the following columns:

Catalyst_Usage (kg)

Energy_Consumption (kWh)

Raw_Material_Input (kg)

Biofuel_Yield (L)

###### View Results:

The program prints a summary of the processed data.
Visualizations are displayed, showcasing resource usage and efficiency.
## Example Output
##### Bar Chart
Compares the usage of catalysts, energy, and raw materials across production runs.
##### Scatter Plot
Displays the relationship between total resource input and biofuel yield, helping identify trends or anomalies.
## Key files
biofuel_analysis.py: The main Python script for data analysis and visualization.
## Contact
For questions or improvements, feel free to reach out!
