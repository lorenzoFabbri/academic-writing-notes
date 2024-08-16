# Data Visualization

## Basic Principles

- Tables and charts should provide information about **who, what, when, where**, including the units.
- Provide both risk difference (a-b) and risk ration (a/b), but also report the individual values (i.e., a and b).
- Report both the direction and size of the associations.
- When summarizing patterns, do not **cherry pick** the numbers nor report all of them in prose.
  - Follow the scheme: generalization (overall pattern) -> example -> exceptions.
- **Associations** can be due to causality, or confounding, or bias, or happenstance.
  - Follow the scheme: is the association causal or spurious? -> is the association statistically significant? -> is the association substantively significant (e.g., *clinically significant*)?
  - With a large enough sample size, even microscopic differences can be statistically significant.
  - One way to provide more information is to include **attributable risk calculations**.

## More Technical Principles

- Always specify the **units**.
  - Scale refers to multiple of units.
  - System of measurement.
- Examine the **distribution** of your (transformed) variables.
  - Comparisons should be made relative to the distribution of values of that variable in your data and research context.
  - Step 1: check the level of each variable and check that *it makes sense*.
  - Step 2: check missing value codes and the distribution of missing values.
  - Step 3: check minimum, maximum, and range.
  - Step 4: check the measures of central tendency (mean, median, modal values, depending on the type of variable).
  - Step 5: check the variability (variance, standard deviation). Or report the *five number summary*: minimum, Q1, median, Q3, maximum.
  - Step 6: check the distribution of scales, indexes, and other created variables.
    - **Combine** variables only if they share a common level of measurement and coding scheme, or standardize them.
- Number of digits and **decimal places**.
  - Unit names should appear only in the column header, not in the table cells.
  - Be **consistent**.

|  | Text or chart |  |  | Table |  |  |
|---|:---:|---|---|:---:|---|---|
| Type of statistic | Total digits | Decimal places | Examples | Total digits | Decimal places | Examples |
| _Integer_ | 3 to 4 | Not applicable | 7 million, 388 | Up to 6 | Not applicable | 7.123 thousand, 388 |
| _Rational number_ | 3 to 4 | 1 to 2 | 32.1, -0.71 | Up to 6 | Up to 4 (enough to show 2 significant digits) | 32.1, -0.71, 0.0043 |
| _Percentage_ | 3 to 4 | 1 if several numbers would round to same value, otherwise none | 72%, 6.1% | 3 to 4 | 2 if several numbers would round to same value, otherwise 1 | 72.1%, 6.12% |
| _Proportion_ | Up to 3 | 3 if several numbers <0.10, otherwise 2 | .36, .0024 | Up to 3 | 3 if several numbers <0.10, otherwise 2 | .36, 0.024 |
| _Monetary value_ | 3 to 4 | None for large denominations, 2 for small | $5 million, $12.34 | 3 to 4 | None for large denominations, 2 for small | $5 million, $12.34 |
| _Ratio_ | Up to 3 | 1 to 2 | 12.7, 0.83 | Up to 4 | 2 if one or more ratios <1.0, otherwise 1 | 12.71, 0.83 |
| _Test statistic_ | 3 to 4 | 2 | $\chi^2$=12.19, t=1.78 | 3 to 4 | 2 | $\chi^2$=12.19, t=1.78 |
| _p-value_ | Up to 3 | 2 | p=0.06, p<0.01 | Up to 3 | 2 for values $\geq$ 0.01, 3 for values <0.01 | p=0.06, p<0.001 |

## Types of quantitative comparisons
