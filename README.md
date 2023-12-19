**Portfolio Project**

# **Life Expectancy and GDP**

## Project Prompt

During this project, you will analyze, prepare, and plot data about GDP and life expectancy from the World Health Organization in order to answer questions in a meaningful way.

After you perform your analysis, you will create a blog post to share your findings on the World Health Organization website.

For this project, you will analyze data on GDP and life expectancy from the World Health Organization and the World Bank to try and identify the relationship between the GDP and life expectancy of six countries.

## Project Objectives

- Complete a project to add to my portfolio.
- Use `Seaborn` and `Matplotlib` to create visualizations.
- Become familiar with presenting and sharing data visualizations.
- Preprocess, explore and analyze data.

## Data

The dataset given is a .csv file. After loaded, we can see that has 96 entries (rows) and 4 columns as follows:

| Column                   | Variable                | Dtype   | Count       | Description                       |
| ------------------------ | ----------------------- | ------- | ----------- | --------------------------------- |
| Country                  | Categorical - Nominal   | object  | 96 non-null | Country                           |
| Year                     | Categorical - Numerical | int64   | 96 non-null | Data taken year                   |
| Life expectancy at birht | Cuantitative            | float64 | 96 non-null | Estimate span of life at birth    |
| GDP                      | Cuantitative            | float64 | 96 non-null | Gross Domestic Product in dollars |

**Data Changes**
First, we see that all the columns start with uppercase letter and for optimizations we can change the names of the columns to easily work with them.

Maybe another change that we can make is the object Dtype in `country` to string Dtype.

## Analysis

**Visualizations**

- Live expentancy evolution by country. Line graph
- GDP evolution by country. Line graph
- Correlation between GDP and Live Expectancy
