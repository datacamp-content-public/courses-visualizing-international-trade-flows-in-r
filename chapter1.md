---
title: 'Importing Data'
description: 'Import data from the UN Comtrade database.'
---

## Import Data

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Import the un_comtrade_data.csv using read_csv frim the readr library. The library has been pre-loaded into your workspace.

`@instructions`
Use read_csv from reader to import the file

`@hint`
`read_csv(file = "un_comtrade_data.csv")`

`@pre_exercise_code`
```{r}
library(reader)
```

`@sample_code`
```{r}

```

`@solution`
```{r}
library(readr)
read_csv(file = "un_comtrade_data.csv")
```

`@sct`
```{r}

```
