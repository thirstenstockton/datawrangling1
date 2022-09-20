Data Import
================

# Data Import CSVs

\#importing packages

library (tidyverse)

library (readr)

litter_df \<- read_csv (“./data_import_examples/FAS_litters.csv”)

litter_df \<- janitor::clean_names(litter_df)

litter_df

head (litter_df)

view (litter_df)

skimr::skim(litter_df)

help (read_csv)

# Other File Formats

``` r
library (readxl)

MLB_df <- read_excel ("./data_import_examples/mlb11.xlsx")
```
