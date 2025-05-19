#   Task-1- World Bank Population Data

This report summarizes the exploratory data analysis (EDA) performed on World Bank population data using the "PRODIGY_DS_01.ipynb" Jupyter Notebook.

##   Dataset Description

The dataset contains World Bank population data, including population figures for various countries and regions across multiple years (1960-2023).

##   Analysis Steps

1.  **Dataset Loading and Initial Inspection:**

    * The notebook loads the population dataset from a CSV file.
    * It displays the first few rows using `data.head()` to provide a quick overview.
    * It prints the column names using `data.columns` to show available variables.
    * It prints the shape of the dataframe using `data.shape` to check dimensions.
    * It checks for missing values using `data.isnull().sum()`.
    * It provides descriptive statistics for numerical columns (years) using `data.describe()`.

2.  **Data Transformation and Visualization:**

    * The code calculates the sum of the population for specific decades (1960s, 1970s, 1980s, 1990s, 2000s, 2010s, and 2020s).
    * It generates a bar chart showing the population of India across decades.
    * It creates a histogram of the population distribution across all countries in the 2010s.

##   Key Observations

    * The analysis reveals the structure of the World Bank population dataset.
    * The visualizations highlight population trends for India and the overall distribution of population sizes.
    * World in Decade 2010's made up 2.02% of Sum of population.
    * 2010's accounted for 21.57% of Sum of population.
    * At 349356941821, World had the highest Sum of population and was 6,48,38,996.41% higher than Tuvalu, which had the lowest Sum of population at 538806.
    * World had the highest Sum of population at 349356941821, followed by IDA & IBRD total and Low & middle income. Tuvalu had the lowest Sum of population at 538806.
    * World accounted for 9.53% of Sum of population.
    * Across all 265 Country Name, Sum of population ranged from 538806 to 349356941821.

##   Sample Visualizations

###   Population of India Across Decades

The bar chart below illustrates the population of India for each decade.

  ![barplot_India](https://github.com/user-attachments/assets/bd4aa0fd-2971-41e5-8e3a-20766b141a7b)


###   Population Distribution Across Countries in the 2010s

The histogram below shows the distribution of population across all countries during the 2010s.

![histplot](https://github.com/user-attachments/assets/a88cf982-b96d-4325-9a23-0be89587ba0c)

    


###   Population Growth of All Countries (Every 10 Years)

 ![barplot](https://github.com/user-attachments/assets/86b2b303-c79d-4239-92fe-026c670a769f)

   

##   Next Steps

    * Further analysis could involve comparing population growth rates across different regions or country classifications.
    * Time series analysis could be used to forecast future population trends.
    * The dataset could be merged with other socioeconomic indicators.



