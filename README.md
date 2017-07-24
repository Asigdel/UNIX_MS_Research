# UNIX_MS_Research
#This will be the collection of bash commands fr my MS Research

# How to add a constant number to a column in unix
```
awk '{$6 = $6+1; print}' Pheno_milk_parity1 | head

```
# One month research in one day
```

 paste -d' ' <(cut -c3-19 DRMS_UFL_Penagaricano_F5_Active.txt ) <(cut -c20-36 DRMS_UFL_Penagaricano_F5_Active.txt) <(cut -c 37-53 DRMS_UFL_Penagaricano_F5_Active.txt) > file1

```
