# UNIX_MS_Research
#This will be the collection of bash commands fr my MS Research

# How to add a constant number to a column in unix
```
awk '{$6 = $6+1; print}' Pheno_milk_parity1 | head

```
