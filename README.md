![](https://github.com/Nalito/Market-Basket-Analysis/blob/main/Images/mba.png)

# Market Basket Analysis with Python

> A project on market basket analysis in Python

# Project Overview

In this project, I performed a market basket analysis on groceries dataset to attract key insights that show which items customers are most likely to purchase together. Market Basket Analysis is the use of data mining and analytical tools to find out with items customers purchase together.
Market Basket Analysis can be used to group items in the supermarket. For example, putting butter on the same shelf as bread would encourage customers to buy bread and butter, thus; leading to more sales and more satisified customers.
I performed this analysis using association rule mining to mine the data for hidden associations and charts to visualize the association rules.

# Installation and Setup

## Codes and Resources Used
- **Editor Used:**  VSCode
- **Python Version:** 3.10.9

## Python Packages Used
- **Data Manipulation:** `pandas` and `numpy`
- **Data Visualization:** `seaborn` and `matplotlib`
- **Association Rule Mining:**  `mlxtend`, `apriori` and `association_rules`


# Code structure

```bash
├── mba.ipynb
├── Images
│   ├── mba.png
│   ├── scatterplot.png
│   ├── heatmap.png
│   ├── parallel coordinates.png
├── Market Basket Analysis - Groceries_dataset.csv
├── README.md
└── .gitignore
```

# Results and evaluation

## Top 10 most purchased groceries
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>antecedents</th>
      <th>consequents</th>
      <th>antecedent support</th>
      <th>consequent support</th>
      <th>support</th>
      <th>confidence</th>
      <th>lift</th>
      <th>leverage</th>
      <th>conviction</th>
      <th>zhangs_metric</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>622</th>
      <td>(rolls/buns)</td>
      <td>(whole milk)</td>
      <td>0.110005</td>
      <td>0.157923</td>
      <td>0.013968</td>
      <td>0.126974</td>
      <td>0.804028</td>
      <td>-0.003404</td>
      <td>0.964550</td>
      <td>-0.214986</td>
    </tr>
    <tr>
      <th>623</th>
      <td>(whole milk)</td>
      <td>(rolls/buns)</td>
      <td>0.157923</td>
      <td>0.110005</td>
      <td>0.013968</td>
      <td>0.088447</td>
      <td>0.804028</td>
      <td>-0.003404</td>
      <td>0.976350</td>
      <td>-0.224474</td>
    </tr>
    <tr>
      <th>695</th>
      <td>(yogurt)</td>
      <td>(whole milk)</td>
      <td>0.085879</td>
      <td>0.157923</td>
      <td>0.011161</td>
      <td>0.129961</td>
      <td>0.822940</td>
      <td>-0.002401</td>
      <td>0.967861</td>
      <td>-0.190525</td>
    </tr>
    <tr>
      <th>694</th>
      <td>(whole milk)</td>
      <td>(yogurt)</td>
      <td>0.157923</td>
      <td>0.085879</td>
      <td>0.011161</td>
      <td>0.070673</td>
      <td>0.822940</td>
      <td>-0.002401</td>
      <td>0.983638</td>
      <td>-0.203508</td>
    </tr>
    <tr>
      <th>550</th>
      <td>(soda)</td>
      <td>(other vegetables)</td>
      <td>0.097106</td>
      <td>0.122101</td>
      <td>0.009691</td>
      <td>0.099794</td>
      <td>0.817302</td>
      <td>-0.002166</td>
      <td>0.975219</td>
      <td>-0.198448</td>
    </tr>
    <tr>
      <th>551</th>
      <td>(other vegetables)</td>
      <td>(soda)</td>
      <td>0.122101</td>
      <td>0.097106</td>
      <td>0.009691</td>
      <td>0.079365</td>
      <td>0.817302</td>
      <td>-0.002166</td>
      <td>0.980729</td>
      <td>-0.202951</td>
    </tr>
    <tr>
      <th>649</th>
      <td>(sausage)</td>
      <td>(whole milk)</td>
      <td>0.060349</td>
      <td>0.157923</td>
      <td>0.008955</td>
      <td>0.148394</td>
      <td>0.939663</td>
      <td>-0.000575</td>
      <td>0.988811</td>
      <td>-0.063965</td>
    </tr>
    <tr>
      <th>648</th>
      <td>(whole milk)</td>
      <td>(sausage)</td>
      <td>0.157923</td>
      <td>0.060349</td>
      <td>0.008955</td>
      <td>0.056708</td>
      <td>0.939663</td>
      <td>-0.000575</td>
      <td>0.996140</td>
      <td>-0.070851</td>
    </tr>
    <tr>
      <th>625</th>
      <td>(yogurt)</td>
      <td>(rolls/buns)</td>
      <td>0.085879</td>
      <td>0.110005</td>
      <td>0.007819</td>
      <td>0.091051</td>
      <td>0.827697</td>
      <td>-0.001628</td>
      <td>0.979147</td>
      <td>-0.185487</td>
    </tr>
    <tr>
      <th>624</th>
      <td>(rolls/buns)</td>
      <td>(yogurt)</td>
      <td>0.110005</td>
      <td>0.085879</td>
      <td>0.007819</td>
      <td>0.071081</td>
      <td>0.827697</td>
      <td>-0.001628</td>
      <td>0.984071</td>
      <td>-0.189562</td>
    </tr>
  </tbody>
</table>
</div>

## Scatterplot Visualization

![](https://github.com/Nalito/Market-Basket-Analysis/blob/main/Images/scatterplots.png)

## Heatmap showing correlation between the the top 10 items
![](https://github.com/Nalito/Market-Basket-Analysis/blob/main/Images/heatmap.png)

## Parallel Coordinates Mapping
![](https://github.com/Nalito/Market-Basket-Analysis/blob/main/Images/parallel%20coordinates.png)
