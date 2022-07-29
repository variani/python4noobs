# dplyr (R) vs. pandas (python)

References

- https://gist.github.com/conormm/fd8b1980c28dd21cfaf6975c86c74d07

## rename

1. Rename all columns

```python
df.columns = ['Name', 'Chr', 'Pos', 'Pval']
```

```r
colnames(df) = c('Name', 'Chr', 'Pos', 'Pval']
```
