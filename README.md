# Abhu-s-Guides
These are a list of notebooks created by me, containing codes to study, revise and/or ramp up under-the-hood knowledge sourced while studying various courses/books/projects
| Guide Name | Link | Description |
|---|---|---|
| **All about NumPy** | [link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/All_about_numpy.ipynb)| NumPy methods including mathematical, logical, shape manipulation, sorting, selecting, basic linear algebra, basic statistical operations, random simulation and much more. | 
| **All about Pandas- assess and clean data** |[link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/All_about_pandas.ipynb)|Step by step guide for for data manipulation and analysis using Pandas. | 
| **All about Data Visualization** | [link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/Visualization.ipynb)| Step by step guide using **Matplotlib and Seaborn**: <br><br>**Distribution Plots**: <ul><li>**Displot**: The distplot shows the distribution of a univariate set of observations; </li><li>**Pairplot**: pairplot will plot pairwise relationships across an entire dataframe (for the numerical columns) and supports a color hue argument (for categorical columns); </li><li>**Rugplot** :they just draw a dash mark for every point on a univariate distribution. They are the building block of a KDE plot; </li><li>**KDEplot** : kdeplots are Kernel Density Estimation plots. These KDE plots replace every single observation with a Gaussian (Normal) distribution centered around that value </li></ul> **Categorical Data Plots**: <ul><li>**Factor plot**: factorplot is the most general form of a categorical plot. It can take in a kind parameter to adjust the plot type: Now called catplot;</li><li> **Boxplot & Violinplot**: boxplots and violinplots are used to shown the distribution of categorical data. A box plot (or box-and-whisker plot) shows the distribution of quantitative data in a way that facilitates comparisons between variables or across levels of a categorical variable. The box shows the quartiles of the dataset while the whiskers extend to show the rest of the distribution, except for points that are determined to be “outliers” using a method that is a function of the inter-quartile range; dodge: **dodge** : When using hue nesting, setting this to True will separate the strips for different hue levels along the categorical axis. Otherwise, the points for each level will be plotted in one swarm.; </li><li>**Stripplot**: The stripplot will draw a scatterplot where one variable is categorical. A strip plot can be drawn on its own, but it is also a good complement to a box or violin plot in cases where you want to show all observations along with some representation of the underlying distribution:; </li><li>**Swarmplot**: The swarmplot is similar to stripplot(), but the points are adjusted (only along the categorical axis) so that they don’t overlap. This gives a better representation of the distribution of values, although it does not scale as well to large numbers of observations (both in terms of the ability to show all the points and in terms of the computation needed to arrange them); </li><li>**Barplot** : barplot is a general plot that allows you to aggregate the categorical data based off some function, by default the mean ; </li><li>**Countplot**: This is essentially the same as barplot except the estimator is explicitly counting the number of occurrences. Which is why we only pass the x value. </li></ul> **Matrix Plots**: Matrix plots allow you to plot data as color-encoded matrices and can also be used to indicate clusters within the data ; <ul><li>**Heatmap**: In order for a heatmap to work properly, your data should already be in a matrix form, the sns.heatmap function basically just colors it in for you;  </li><li>**Clustermap**:The clustermap uses hierarchal clustering to produce a clustered version of the heatmap </li></ul> **Grids** are general types of plots that allow you to map plot types to rows and columns of a grid, this helps you create similar plots separated by features; <ul><li> **PairGrid**: Pairgrid is a subplot grid for plotting pairwise relationships in a dataset.; </li><li>**Facet Grid**: FacetGrid is the general way to create grids of plots based off of a feature|
| **Statistics and Hypothesis Testing** | [link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/Statistics.ipynb)| <ul><li> **Continuous Data**: Z test ; 1-sample t-test ; Means for two groups:2-sample t-test ; Paired t ; Comparing CIs ; Means for at least three groups: One-way ANOVA ; Two Way ANOVA ; Compare specific groups from ANOVA:  Post hoc tests; Tukey’s Method ; Dunnett’s Method ;Hsu’s MCB ; One standard deviation to reference: 1 Sample Variance Test ; Standard deviations for two groups :2 Sample Variance Test ; Correlation between two continuous variables: Pearson’s correlation coefficient ; Medians: Nonparametric tests, Mann-Whitney Test  </li><li>**Binary Data**:One proportion to a target : 1 Proportions Test ; Proportions for two groups: 2 Proportions Test ; Control chart: P control chart </li><li>**Count Data**: Do your counts follow the Poisson distribution?: Poisson Goodness-of-Fit Test ; One rate to a target: 1 Sample Poisson Rate Test ; Rates for two groups: 2 Sample Poisson Rate Test </li><li>**Categorical Data**: Association between two categorical variables: Chi-Squared Test of Independence ; Do the proportions of values follow a hypothesized distribution?: Chi-Square Goodness-of-Fit test </li><li>**Ordinal and Ranked Data**:Medians, Ordinal and Ranked data: Nonparametric tests, Mann-Whitney Test ; Correlation between variables: Spearman’s Rank Correlation ; Kendall’s Rank Correlation ; </li><li>**Various: Bootstrapping Methods** </li><li>**Stationary Tests**:Augmented Dickey-Fuller ; Kwiatkowski-Phillips-Schmidt-Shin ; Nonparametric Statistical Hypothesis Tests; Mann-Whitney Test: </li><li>**Ordinal and Ranked data**: Friedman Test : Data should be ordinal (e.g. the Likert scale) or continuous ; Wilcoxon Signed-Rank Test: interval or ratio data ; Kruskal-Wallis H Test: Ordinal scale, Ratio Scale or Interval scale dependent variables. </li><li>**Theory**: Means ; Normal Distribution ; Useful Commands ; Errors ; Power ; Directional vs Non Directional ; Effect Size  |
| **A/B Testing - solid base**|[link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/Analyze_ab_test_results_notebook.ipynb)| <ul><li> Step 1: Calculate sample size, decide practical significance /mde </li><li>Step 2: Choose and characterize metrics for both **sanity check and evaluation** </li><li>Step 3: Designing an experiment </li><li>Step 4: Analyzing Results </li><li> **Simple Sequential A/B Testing** </li><li>Comparing Classic and Sequential A/B Tests |
| **Regression**| [link]()|Asssumptions, Types, Feature scaping, Data Interpretation, Intuituon building, model building|
| **Classification** |[link]()|Asssumptions, Types, Feature scaping, Data Interpretation, Intuituon building, model building|
| **Deep Learning** |[link]()|Asssumptions, Types, Feature scaping, Data Interpretation, Intuituon building, model building|
| **SQL** |[link](https://github.com/Abhudeep/Abhu-s-Guides/blob/main/SQL.ipynb)|Comprehensive sql tutorial : <ul><li> **Basic SQL**: Introduction to SQL; SELECT FROM statement; WHERE statement; ORDER BY statement, LIMIT statement, DISTINCT </li><li>**LOGICAL and COMPARISON Operators** </li><li>**Aggregates**: Aggregate Functions (COUNT, SUM, MIN/MAX, AVG); GROUP BY clause; HAVING clause </li><li>**Conditional Expressions**: CASE WHEN, COALESCE, IFNULL</li><li>**JOINS and UNIONS**</li><li>**Subqueries and Common Table Expressions**</li><li>**String Manipulations**</li><li>**Date-time manipulation**: EXTRACT, DATE_ADD(), DATE_SUB(), DATE_DIFF()</li><li>**Windows Functions**: ROW_NUMBER(), RANK(), DENSE_RANK(), LAG, LEAD, SUM, COUNT, AVG|

