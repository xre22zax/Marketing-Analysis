# Marketing Analysis


## Overview

This is analysis of marketing data to uncover relationships between customer demographics, purchasing behaviors, and product preferences. The insights derived from this analysis can inform targeted marketing strategies and enhance customer engagement.

---

## Key Findings :

1.	Does a shopper's education level relate to their purchasing behavior?
2.	Does a shopper's income relate to their purchasing behavior?
3.	Does a shopper's age relate to their purchasing behavior?
4.	Does a shopper's country relate to their purchasing behavior?
5.	Does a shopper's number of web visits relate to their overall purchasing?
6.	Does a shopper's marital Status relate to their purchasing behavior?
7.	Having kids or teens at home affect and relate to purchasing behavior?


---

## Libraries Used :

+ pandas
+ numpy
+ seaborn
+ matplotlib.pyplot
+ re

---

## Methods Employed

This analysis leverages a variety of techniques to extract insights from customer data:

**Data Manipulation:**

* **Preparing the data for exploration:**
    - Identifying and handling missing values (`isnull`, `sum`, `replace`)
    - Cleaning and formatting text data (`regex`, `astype`, `re.sub`, `lower`)
    - Creating efficient data transformations (`lambda`, `for`, `fillna`, `mean`)
* **Understanding data characteristics:**
    - Summarizing statistical measures (`describe`)
    - Selecting specific data types (`select_dtypes`)
    - Examining relationships between variables (`corr`)
* **Structuring data for analysis:**
    - Creating lists and calculating lengths (`list`, `len`, `range`)
    - Formatting numerical values (`format`)
    - Defining custom functions (`function`, `if`, `apply`)
    - Handling categorical data (`Categorical`, `loc`)
    - Categorizing numerical data (`bins`, `cut`, `groupby`)
    - Reshaping data for visualization (`reset_index`, `melt`)

**Data Visualization:**

* **Creating insightful visualizations:**
    - Generating base plots (`figure`)
    - Visualizing distributions (`boxplot`, `clf`, `order`, `figsize`, `fig.gca()`, `tight_layout`)
    - Highlighting correlations (`heatmap`, `annot`)
    - Customizing subplot arrangements (`axes`, `subplots`, `nrows`, `ncols`, `hue`, `palette`)
    - Adding informative labels (`set_title`, `set_xlabel`, `legend`, `loc`)
    - Saving visualizations for sharing (`savefig`)
    - Exploring relationships between variables (`scatterplot`, `regplot`, `scatter_kws`, `line_kws`)
    - Enhancing plot readability (`flatten`, `tick_params`, `rotation`)
    - Generating faceted visualizations (`FacetGrid`, `col_wrap`)
    - Visualizing categorical data distributions (`map`, `countplot`)
    - Customizing plot types (`kind`, `width`, `edgecolor`, `color`, `xticks`)


---

### Getting Started

1. Clone this repository.
2. Install the required libraries: pip install pandas numpy seaborn matplotlib re
3. Run the main Python script: Marketing Analysis.ipynb

---

### Usage

- Explore the generated visualizations to gain insights into the data.
- Modify the code to experiment with different visualizations and analyses.

---


#### Contributing

Feel free to submit issues or pull requests for improvements or additions.

---

#### Author

[Reza Sadeghi](https://github.com/xre22zax/)
