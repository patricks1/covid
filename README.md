This code automatically pulls SARS-CoV-2 data from government websites, automatically pulls population data from the U.S. census, and plots population-adjusted daily new cases data. I made this because I did not find an existing way to make a per-capita comparison of how well of poorly different states and counties are doing.

# sources.csv
`sources.csv` is read as `state`, `source_url`, `name_of_target_column`, `name_of_date_column`, `name_of_county_column`. Right now the code is cabable of creating plots for CA, NY, NC, and FL. If we want to add any more states, we need to add the source location and column instructions to `sources.csv`.
