POSTER PRESENTATION: [Updated Hypothesis Poster.pptx](https://github.com/user-attachments/files/17448127/Updated.Hypothesis.Poster.pptx)

---

# **Analysis of Goal Scoring Patterns in International Soccer Tournaments: Men vs. Women**

This project analyzes and compares the goal-scoring patterns in five major international soccer tournaments across men’s and women’s teams. Using hypothesis testing, statistical analysis, and visualizations, the project aims to provide insights into the differences and similarities in goal-scoring between men and women in the selected tournaments.

## **Project Overview**
This study was conducted to investigate whether there is a statistically significant difference in the total goals scored in international soccer tournaments between men's and women's teams. The focus is on five major tournaments:
- FIFA World Cup
- UEFA European Championship
- Copa América
- African Cup of Nations
- AFC Asian Cup

Using hypothesis testing, the project aims to determine whether there are differences in scoring patterns, and what that means for stakeholders such as betting companies, based on statistical significance.

## **Project Structure**

- **`data/`**: Contains the datasets for both men's and women's soccer matches.
- **`notebooks/`**: Jupyter Notebooks containing the analysis, data processing, and statistical testing.
- **`images/`**: Visualizations used for the analysis and in the final report.
- **`README.md`**: Project overview and instructions.
- **`results/`**: Contains summary results of the statistical tests performed, including p-values and hypothesis test outcomes.

## **Data Sources**
The data consists of match-level records including the following key attributes:
- **Home Score**: Goals scored by the home team.
- **Away Score**: Goals scored by the away team.
- **Tournament**: The tournament where the match was played.
- **Date**: Date of the match.
  
## **Methodology**
1. **Data Cleaning & Preprocessing**: The data is cleaned and aggregated to calculate the total goals per match.
2. **Normality Testing**: The Shapiro-Wilk test is used to check if the data follows a normal distribution.
3. **Hypothesis Testing**: 
   - For normally distributed data, a **t-test** was used to compare the means between men’s and women’s tournaments.
   - For non-normally distributed data, a **Mann-Whitney U test** was used to compare the medians.
   - A **Bonferroni correction** was applied to adjust for the multiple comparisons across the tournaments.
4. **Visualizations**: Line plots, box plots, and bar charts were created to present the distributions and results of the analysis.

## **Results**
- **World Cup**: Statistically significant difference in goals between men’s and women’s teams (p = 0.003).
- **EUROs**: No statistically significant difference found (p = 0.110).
- **Copa América**: Statistically significant difference in goals (p = 0.000).
- **EURO Qualifiers**: Statistically significant difference found (p = 0.000).
- **AFC Asian Cup**: Statistically significant difference found (p = 0.000).

## **Conclusions and Recommendations**
- For tournaments where there was a significant difference, betting companies should consider offering adjusted odds based on the tournament’s goal patterns for men vs. women.
- For tournaments with no significant difference, standard odds can be maintained as goal-scoring patterns between men’s and women’s teams are similar.
  
## **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/soccer-goal-analysis.git
   ```
2. **Run Jupyter Notebooks**: Open the notebooks to run the code for data cleaning, analysis, and visualization.
   ```bash
   jupyter notebook
   ```
3. **Install Dependencies**: Install required libraries (if necessary).
   ```bash
   pip install -r requirements.txt
   ```

## **Technologies Used**
- **Python**: For data analysis, visualization, and hypothesis testing.
- **Pandas**: For data manipulation and aggregation.
- **SciPy**: For performing statistical tests.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Google Colab**: The project was developed using Google Colab.

## **Contact**
For any questions, feel free to reach out:
- **Email**: your.email@example.com
- **LinkedIn**: (https://www.linkedin.com/in/ukeje-ugochukwu/)
- **GitHub**: (https://github.com/DaytaHokage/Soccer-Hypothesis-Testing/edit/main/README.md))

---

