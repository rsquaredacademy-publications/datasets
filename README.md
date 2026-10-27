This repository has all the data sets used in the blog posts,interactive 
tutorials and online courses of Rsquared Academy. 

## Course data sets

### `weather.csv` (Intro to R)

Daily weather for three Indian cities (Pune, Mumbai, Bengaluru) over 20 days
in June 2026: 60 rows, columns `date`, `city`, `temp_c`, `rain_mm`, `sunny`.
Generated for the course; own data, CC0. Also in the
[rsquareddata](https://github.com/rsquaredacademy-publications/rsquareddata)
package as `weather`.

### `store_days.csv` (Data Viz with ggplot2)

Bean & Barrel coffee chain: one row per store per trading day, 9 stores in
5 countries × 20 days in March 2026 (180 rows). Columns `day`, `date`,
`store_id`, `city`, `country`, `customers`, `revenue_usd`, `avg_spend_usd`
(revenue per customer), `avg_wait_min`.
Generated for the course (seed 20260314); own data, CC0. Also in the
[rsquareddata](https://github.com/rsquaredacademy-publications/rsquareddata)
package as `store_days`.

### `sales.csv` and `stores.csv` (Data Wrangling with dplyr, Data Viz with ggplot2)

Bean & Barrel coffee chain. `sales.csv`: one row per sale, 160 sales over
20 days in March 2026, columns `sale_id`, `sale_date`, `store_id`, `product`,
`size`, `units`, `revenue_usd`. `stores.csv`: one row per store (9 stores),
columns `store_id`, `store_name`, `city`, `country`, `opened_year`, `seats`;
joins to `sales.csv` on `store_id`. Generated for the courses; own data, CC0.
Also in the
[rsquareddata](https://github.com/rsquaredacademy-publications/rsquareddata)
package as `sales` and `stores`.
