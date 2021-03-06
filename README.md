
# modelplotr: Plots to evaluate the business value of predictive models

The modelplotr package makes it easy to create a number of valuable
evaluation plots to assess the business value of a predictive model.
Using these plots, it can be shown how implementation of the model will
impact business targets like response or return on investment of a
campaign.

Plots available with modelplotr:

  - cumulative gains
  - cumulative lift
  - response
  - cumulative response
  - costs & revenues
  - profit
  - return on investment

Some benefits of using modelplotr:

  - *easy to explain* plots to discuss your model with business
  - *easy to use* on top of predictive models built with caret, mlr,
    h2o, keras or otherwise (with or without r)
  - supports both *binary and multinomial targets*
  - provides *four plotting scopes*:
      - comparing models
      - comparing datasets
      - comparing multiclass target classes
      - no comparison (single line)
  - *plot annotation*: highlighting specific values and adding
    explanatory text to guide interpretation
  - *plot customization*: all textual elements, line colors
  - *save plot* to file on disk

## Installation

You can install `modelplotr` from
[GitHub](https://github.com/modelplot/modelplotr) with:

``` r
devtools::install_github("modelplot/modelplotr")
```

See this blog for further details and examples of using the package.
