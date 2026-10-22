# Stats

**Category:** LIBRARY | **Subcategory:** Standard Library (Math)

## Summary
Descriptive statistics, variance, standard deviation, linear regression, median, quartiles, and correlation.

## Syntax
```verscript
load Stats
Stats.mean(arr)
Stats.median(arr)
Stats.variance(arr)
Stats.stdDev(arr)
```

## Parameters / Arguments
- `dataset` *(arr of num)*: undefined

## Runnable Code Example
```verscript
load Stats
set samples : [12, 15, 18, 22, 30]
display "Median: " + Stats.median(samples) ?color=#22c55e
```
