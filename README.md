# RescueDataClusters

```python
corr = df_numeric_categories.corr().loc[
    'breed_grouped_Mixed breed', 'sex_upon_intake_Intact'
]
print(corr)          # if ≥ 0.9 they’re redundant
```
