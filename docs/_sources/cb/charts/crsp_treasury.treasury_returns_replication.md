---
date: "2026-07-09 20:46:16"
tags: "CRSP Treasury Database"
category: "Treasury, Bonds, Returns, Replication"
---

# Chart: Treasury Bond Portfolio Returns
Treasury bond portfolio returns from CRSP data

## Chart
```{raw} html
<iframe src="../../_static/crsp_treasury/treasury_returns_replication.html" height="500px" width="100%"></iframe>

<p style="text-align: center;">Sources: CRSP Treasury Database</p>
```
[Full Screen Chart](../download_chart/crsp_treasury/treasury_returns_replication.html)





## Treasury Bond Portfolio Returns

Monthly Treasury bond returns from CRSP, grouped by maturity bucket.

### Maturity Groups

10 groups spanning 0-5 years in 6-month intervals.

### Data Source

CRSP US Treasury Database via WRDS



## Chart Specs

| Chart Name             | Treasury Bond Portfolio Returns                                             |
|------------------------|------------------------------------------------------------|
| Chart ID               | treasury_returns_replication                                               |
| Topic Tags             | Treasury, Bonds, Returns, Replication                                |
| Data Series Start Date |                                  |
| Data Frequency         |                                          |
| Observation Period     |                                      |
| Lag in Data Release    |                                     |
| Data Release Timing    |                                     |
| Seasonal Adjustment    |                                     |
| Units                  |                                                   |
| HTML Chart             | [HTML](../download_chart/crsp_treasury/treasury_returns_replication.html)    |


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
| Data available up to (min)     |                                                              |
| Data available up to (max)     |                                                              |
| Dataframe Path                 | /Users/jbejarano/GitRepositories/ftsfr_repos/crsp_treasury/_data/ftsfr_treas_bond_portfolio_returns.parquet                                                   |


**Linked Charts:**


- [crsp_treasury:treasury_returns_replication](../../charts/crsp_treasury.treasury_returns_replication.md)

- [crsp_treasury:treasury_cumulative_returns](../../charts/crsp_treasury.treasury_cumulative_returns.md)



## Pipeline Manifest

| Pipeline Name                   | CRSP Treasury                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [crsp_treasury](../../index.md)              |
| Lead Pipeline Developer         | Jeremiah Bejarano             |
| Contributors                    | Jeremiah Bejarano           |
| Git Repo URL                    | https://github.com/ftsfr/crsp_treasury                        |
| Pipeline Web Page               | <a href="file:///Users/jbejarano/GitRepositories/ftsfr_repos/crsp_treasury/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-07-09 20:46:16           |
| OS Compatibility                |  |
| Linked Dataframes               |  [crsp_treasury:crsp_treasury_daily](../dataframes/crsp_treasury/crsp_treasury_daily.md)<br>  [crsp_treasury:treasury_auctions](../dataframes/crsp_treasury/treasury_auctions.md)<br>  [crsp_treasury:ftsfr_treas_bond_portfolio_returns](../dataframes/crsp_treasury/ftsfr_treas_bond_portfolio_returns.md)<br>  |

