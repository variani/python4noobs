# dplyr (R) vs. pandas (python)

## rename

1. Rename all columns

```python
df.columns = ['Name', 'Chr', 'Pos', 'Pval']
```

```r
colnames(df) = c('Name', 'Chr', 'Pos', 'Pval']
```
