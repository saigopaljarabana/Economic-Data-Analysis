# Economic Data Analysis with Fred & Pandas

This project is a data analysis project using the Fred API and Python libraries. The goal is to pull economic data, visualize it, and discover insights using Python and Pandas.

1. **Setup:**
   - Install necessary libraries using `pip install -r requirements.txt`.
   - Configure API key in `config.ini` for accessing the FRED API.

2. **Search for S&P Economic Data:**
   - Query the FRED database for economic data related to the S&P index.
   - Display the search results, including series IDs, titles, and additional information.

3. **Plotting S&P 500 Data:**
   - Fetch the S&P 500 data from FRED using the series ID 'SP500'.
   - Visualize the data using matplotlib with a line plot.

4. **Fetching and Processing Unemployment Rate Data for States:**
   - Search for unemployment rate data for states with monthly frequency.
   - Filter and process the data, creating a DataFrame with state-wise unemployment rates.
   - Plot the unemployment rates using Plotly Express.

5. **Bar Chart: Unemployment Rate by State (May 2023):**
   - Create a horizontal bar chart for the unemployment rate by state in May 2023.

6. **Labor Force Participation Rate by State:**
   - Search for labor force participation rate data for states.
   - Process the data, creating a DataFrame with state-wise participation rates.
   - Plot the unemployment and participation rates for multiple states over time.

7. **Plot Unemployment and Participation Rates for a Specific State (e.g., Massachusetts):**
   - Plot the unemployment and participation rates for a specific state over time.

## Outputs

- **Search Results:** Displayed search results for S&P economic data and unemployment rate data for states.
- **S&P 500 Plot:** Visual representation of the S&P 500 data.
- **Unemployment Rate Plot:** Line plot depicting the unemployment rates for different states.
- **Bar Chart:** Bar chart showing the unemployment rates by state in May 2023.
- **Labor Force Participation Plot:** Multiple subplots illustrating the unemployment and participation rates for various states over time.
- **State-specific Plot:** Plot of unemployment and participation rates for a specific state (e.g., Massachusetts).

## Running the Project Locally

1. **Clone the Repository:**
   - Clone this GitHub repository to your local machine.

2. **Install Dependencies:**
   - Run `pip install -r requirements.txt` to install the required libraries.

3. **Configure API Key:**
   - Obtain a FRED API key and update it in the `config.ini` file.

4. **Run the Jupyter Notebook:**
   - Open and run the Jupyter Notebook file (`project_analysis.ipynb`).
   - Ensure you have a Jupyter Notebook environment set up.

5. **Explore and Modify:**
   - Explore the code, visualizations, and analysis in the Jupyter Notebook.
   - Modify and customize the project according to your requirements.

**Note:** Make sure to check the code comments for detailed explanations and insights throughout the notebook.
