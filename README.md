# Programming language analysis
Analyzing Programming Language Trends on Stack Overflow (2008-2020)     
## Project Overview
This project analyzes the popularity trends of programming languages over a 12-year period by examining the volume of questions tagged on Stack Overflow. By processing and visualizing this data, we can identify which languages have grown, which have declined, and pinpoint significant trends in the software development landscape.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)

## Objectives
To acquire and clean a real-world, time-series dataset.

To utilize Python's data analysis stack (Pandas, Matplotlib, Seaborn) for data manipulation and visualization.

To identify and visualize long-term trends in programming language discussion.

To draw meaningful insights about the evolution of technology preferences among developers.

## Dataset
Source: Publicly available Stack Overflow data query.

Content: The file (QueryResults.csv) contains monthly data from July 2008 to July 2020. Each row represents the number of posts (PostCount) for a specific programming language (TagName) in a given month (m).

Original Schema: m (date), TagName (string), PostCount (int)

## Process / Methodology
Data Loading & Inspection: Loaded the CSV into a Pandas DataFrame and performed an initial inspection to understand its structure, check for missing values, and identify data types.

## Data Cleaning,wrangling and visualisation

Parsed the m column into a proper DateTime object.

Checked for and handled any inconsistencies in TagName (e.g., case sensitivity, typos).

Pivoted the data to create a time-series DataFrame with languages as columns.

Data Analysis & Transformation: Calculated metrics such as total posts per language and normalized trends to better compare growth rates despite absolute volume differences.

Data Visualization: Created multiple plots to tell the story of the data:

Line Plot of Absolute Popularity: To show the raw volume of posts over time.

Line Plot of Relative Popularity/Rank: To compare the growth trajectories on a more equal footing.

Focus on Specific Languages: Highlighting the rise of Python, the stability of JavaScript/Java, etc.

## Key Insights & Visualizations
### 1. The Rise of Python
Python dgrowth trajectory,surpasses Java particularly after 2017. This surge correlates with its rising dominance in data science, machine learning, and DevOps.
![Python Growth Plot](https://github.com/Patphade1985/Programming-language-analysis/blob/faef4b8f40f6bbb3c45c923362e6601a19224aaa/Graphs/download%20(3).png)

### 2. The Mainstays: JavaScript and Java
JavaScript and Java maintained consistently high volumes of discussion throughout the entire period, underscoring their foundational and enduring role in web and enterprise development.
![Mainstays Plot](https://github.com/Patphade1985/Programming-language-analysis/blob/0257bb7058c175e53e8657cf4573fc3ca2def8be/Graphs/download%20(6).png)

## 🔗 Links
- [LinkedIn](https://linkedin.com/in/your-profile)
- [Portfolio](https://your-portfolio-website.com)

# How to Run This Project
Clone the repository:

bash
git clone https://github.com/your-username/stackoverflow-trends.git
cd stackoverflow-trends
Install the required libraries:

bash
pip install -r requirements.txt
(Create a requirements.txt file with: pandas, matplotlib, seaborn, jupyter)

Open the Jupyter Notebook:

bash
jupyter notebook analysis.ipynb
Run the cells in the notebook to see the step-by-step analysis and generate the graphs.

## Technologies Used
Python: Core programming language.

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For creating static, animated, and interactive visualizations.

Jupyter Notebook: For an interactive and documented coding environment.

## Conclusion
This analysis provides a data-backed look into the evolving trends of programming languages. It highlights the rapid growth of Python, the stability of established giants, and the life cycle of newer technologies. The skills demonstrated here—data cleaning, processing, visualization, and interpretation—are directly applicable to real-world data analysis and business intelligence tasks.

## 🔗 Links
- [LinkedIn](https://linkedin.com/in/your-profile)

