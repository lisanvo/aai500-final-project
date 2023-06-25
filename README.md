# Bike Sharing Usage
This project is a part of the AAI-500 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 
<br><br>**Project Status: ACTIVE**

## Introduction
For this project, we analyze bike sharing usage count against season, temperature, and humidity to explain the likely causes of high bike sharing usage between seasons in 2011-2012 using multiple linear regression with analysis of variance (ANOVA) testing. Our goal is to inform stakeholders who are interesting in expanding bike sharing to untapped markets.

## Contributors
- Angel Benitez
- Zack Robertson
- Lisa Vo

## Local Installation
Run the following command:

```
git clone git@github.com:lisanvo/aai500-final-project.git
```

To contribute to this project:
1. Create a branch with a descriptive name.
2. Push changes to your branch.
3. Open a pull request and have team members do a code review.
4. Merge PR after it is reviewed and approved.

### Troubleshooting

To learn how to generate and add an SSH key, go [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Methods Used
- Descriptive statistics
- Inferential statistics
- Data manipulation
- Generalized linear models
- Significance testing
	
## Technologies
- Python
- Jupyter notebooks
- Github Codespaces
- Frameworks:
    - matplotlib
    - numpy
    - pandas
    - scikit-learn
    - scipy
    - seaborn
    - statsmodels

## Project Description
We explore whether season had an impact on bike sharing usage in 2011-2012. If there is an effect, we analyze what are the likely causes that would lead one season having a higher bike sharing usage count than that of another season. We encode categorical columns and drop columns that are irrevelant in order to make our modeling more efficient and to reduce multicollinearity. We run simple and multiple linear regression with ANOVA testing to analyze our data. Forms of data visualization we use are scatterplots, correlation matrices, heat maps, box-plots, bar graphs, histograms, and violin plots. Our dataset can be found [here](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset). 
