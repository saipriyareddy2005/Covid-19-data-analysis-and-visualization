# Covid-19-data-analysis-and-visualization
This project performs data analysis and visualization on COVID-19 datasets using **Python (Pandas, Matplotlib, and Plotly)**. It explores case numbers, death rates, and recovery statistics across different regions.

## Features
- **Data Cleaning & Manipulation**: Removes unnecessary columns and processes data.
- **Statistical Summary**: Provides dataset shape, size, and column details.
- **Interactive Visualizations**:
  - Bar charts for case distribution
  - Scatter plots for continent-wise cases
  - Choropleth maps showing COVID-19 spread over time
  - Word clouds for COVID-related conditions
- **Multiple Dataset Support**: Works with different COVID-19 datasets.

## Technologies Used
- **Python** (Pandas, Matplotlib, Plotly, WordCloud)
- **Jupyter Notebook / Google Colab** (For interactive analysis)
- **Plotly Express & Graph Objects** (For interactive visualizations)

## Project Structure
```
📁 Covid19_Analysis
│── 📄 covid_19_analysis.py  # Python script for data analysis
│── 📄 covid.csv             # Dataset 1 (General COVID-19 cases)
│── 📄 covid_grouped.csv     # Dataset 2 (Grouped COVID-19 data)
│── 📄 coviddeath.csv        # Dataset 3 (COVID-19 death conditions)
```

## How to Run
1. **Clone the repository:**
   ```sh
   git clone https://github.com/YOUR_USERNAME/Covid19_Analysis.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Covid19_Analysis
   ```
3. **Install dependencies:**
   ```sh
   pip install pandas matplotlib plotly wordcloud
   ```
4. **Run the Python script:**
   ```sh
   python covid_19_analysis.py
   ```
5. **For Jupyter Notebook:**
   - Open `covid_19_analysis.ipynb` in Jupyter Notebook or Google Colab.

## How to Upload to GitHub
1. Initialize a new Git repository:
   ```sh
   git init
   ```
2. Add all project files:
   ```sh
   git add .
   ```
3. Commit the changes:
   ```sh
   git commit -m "Initial commit - COVID-19 Analysis"
   ```
4. Create a new GitHub repository and link it:
   ```sh
   git remote add origin https://github.com/YOUR_USERNAME/Covid19_Analysis.git
   ```
5. Push the project to GitHub:
   ```sh
   git branch -M main
   git push -u origin main
   ```

