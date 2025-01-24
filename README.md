# Common Statistical Tests: A Case Study  

This repository provides a comprehensive case study on common statistical tests, utilizing a dataset that explores the effects of diet types on weight loss over six weeks.  

## Files in this Repository  

- **`common_stats_2.ipynb`**  
  A Jupyter Notebook demonstrating the implementation of statistical tests, data preprocessing, visualization, and result interpretation.  

- **`Common StatisticalTest - case_study_2.csv`**  
  The dataset used in the case study, containing information about diet types, weight changes, and age.  

## Dataset Overview  

The dataset contains 78 entries with the following columns:  
- **`diet`**: Categorical variable indicating diet type (A or B).  
- **`preweight`**: Initial weight of the subjects before the experiment.  
- **`weight6weeks`**: Weight of the subjects after six weeks.  
- **`age`**: Age of the subjects.  

A derived column, **`weight_loss`**, is computed as the difference between `preweight` and `weight6weeks`. Additionally, **`age_category`** groups ages into:  
- 18-25  
- 25-40  
- 40+  

## Statistical Tests and Techniques  

The following statistical methods are explored in the notebook:  

1. **Data Visualization**  
   - Histograms and boxplots for understanding weight distribution and loss.  
   - Bar plots to visualize group differences.  

2. **Hypothesis Testing**  
   - **One-way ANOVA**: Analyze weight loss differences between diet groups.  
   - **T-tests**: Pairwise comparisons of means for specific subgroups.  

3. **Regression Analysis**  
   - Simple linear regression to evaluate the relationship between age and weight loss.  

4. **Correlation Analysis**  
   - Assess correlations between variables, e.g., age and weight loss.  

## Prerequisites  

To run the Jupyter Notebook  

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scipy  
- statsmodels  


