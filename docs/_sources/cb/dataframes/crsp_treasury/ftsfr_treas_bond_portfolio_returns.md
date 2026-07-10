# Dataframe: `crsp_treasury:ftsfr_treas_bond_portfolio_returns` - ftsfr_treas_bond_portfolio_returns

## Treasury Bond Portfolio Returns

This dataset contains portfolio returns grouped by maturity buckets.

### Columns

| Column | Description |
|--------|-------------|
| unique_id | Maturity group (1-10, representing 6-month intervals from 0-5 years) |
| ds | Month-end date |
| y | Average monthly return for the maturity group |

### Maturity Groups

| Group | Maturity Range |
|-------|----------------|
| 1 | 0 to 6 months |
| 2 | 6 months to 1 year |
| 3 | 1 year to 1.5 years |
| 4 | 1.5 to 2 years |
| 5 | 2 to 2.5 years |
| 6 | 2.5 to 3 years |
| 7 | 3 to 3.5 years |
| 8 | 3.5 to 4 years |
| 9 | 4 to 4.5 years |
| 10 | 4.5 to 5 years |

### Data Source

CRSP US Treasury Database via WRDS



## DataFrame Glimpse

```
Rows: 6699
Columns: 3
$ unique_id          <str> '10'
$ ds        <datetime[ns]> 2025-12-31 00:00:00
$ y                  <f64> -0.0014417265994031067


```

## Dataframe Manifest

| Dataframe Name                 | ftsfr_treas_bond_portfolio_returns                                                   |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [ftsfr_treas_bond_portfolio_returns](../dataframes/crsp_treasury/ftsfr_treas_bond_portfolio_returns.md)                                       |
| Data Sources                   | CRSP Treasury Database                                        |
| Data Providers                 | WRDS                                      |
| Links to Providers             | https://wrds-www.wharton.upenn.edu/                             |
| Topic Tags                     | Treasury, Bonds, Portfolios, Returns                                          |
| Type of Data Access            | WRDS Subscription                                  |
| How is data pulled?            | Pulled from WRDS CRSP Treasury Database                                                    |
| Data available up to (min)     | 2025-12-31 00:00:00                                                             |
| Data available up to (max)     | 2025-12-31 00:00:00                                                             |
| Dataframe Path                 | /Users/jbejarano/GitRepositories/ftsfr_repos/crsp_treasury/_data/ftsfr_treas_bond_portfolio_returns.parquet                                                   |


**Linked Charts:**


- [crsp_treasury:treasury_returns_replication](../../charts/crsp_treasury.treasury_returns_replication.md)

- [crsp_treasury:treasury_cumulative_returns](../../charts/crsp_treasury.treasury_cumulative_returns.md)



## Pipeline Manifest

| Pipeline Name                   | CRSP Treasury                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [crsp_treasury](../../../index.md)              |
| Lead Pipeline Developer         | Jeremiah Bejarano             |
| Contributors                    | Jeremiah Bejarano           |
| Git Repo URL                    | https://github.com/ftsfr/crsp_treasury                        |
| Pipeline Web Page               | <a href="file:///Users/jbejarano/GitRepositories/ftsfr_repos/crsp_treasury/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-07-09 20:46:16           |
| OS Compatibility                |  |
| Linked Dataframes               |  [crsp_treasury:crsp_treasury_daily](../../dataframes/crsp_treasury/crsp_treasury_daily.md)<br>  [crsp_treasury:treasury_auctions](../../dataframes/crsp_treasury/treasury_auctions.md)<br>  [crsp_treasury:ftsfr_treas_bond_portfolio_returns](../../dataframes/crsp_treasury/ftsfr_treas_bond_portfolio_returns.md)<br>  |


