# CRSP Treasury

Last updated: {sub-ref}`today`



## Table of Contents

```{toctree}
:maxdepth: 1
:caption: Notebooks 📖
summary_treasury_bond_returns_ipynb <cb/notebooks/crsp_treasury/summary_treasury_bond_returns_ipynb>
```



```{toctree}
:maxdepth: 1
:caption: Pipeline Charts 📈
cb/charts.md
```

```{postlist}
:format: "{title}"
```


```{toctree}
:maxdepth: 1
:caption: Pipeline Dataframes 📊
cb/dataframes/crsp_treasury/crsp_treasury_daily.md
cb/dataframes/crsp_treasury/ftsfr_treas_bond_portfolio_returns.md
cb/dataframes/crsp_treasury/treasury_auctions.md
```


```{toctree}
:maxdepth: 1
:caption: Appendix 💡
myst_markdown_demos.md
apidocs/index
```


## Pipeline Specs
| Pipeline Name                   | CRSP Treasury                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [crsp_treasury](./index.md)              |
| Lead Pipeline Developer         | Jeremiah Bejarano             |
| Contributors                    | Jeremiah Bejarano           |
| Git Repo URL                    | https://github.com/ftsfr/crsp_treasury                        |
| Pipeline Web Page               | <a href="file:///Users/jbejarano/GitRepositories/ftsfr_repos/crsp_treasury/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-07-09 20:46:16           |
| OS Compatibility                |  |
| Linked Dataframes               |  [crsp_treasury:crsp_treasury_daily](cb/dataframes/crsp_treasury/crsp_treasury_daily.md)<br>  [crsp_treasury:treasury_auctions](cb/dataframes/crsp_treasury/treasury_auctions.md)<br>  [crsp_treasury:ftsfr_treas_bond_portfolio_returns](cb/dataframes/crsp_treasury/ftsfr_treas_bond_portfolio_returns.md)<br>  |



A data pipeline for processing U.S. Treasury securities data from CRSP and TreasuryDirect, including on-the-run/off-the-run status calculations.

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/ftsfr/crsp_treasury.git
   cd crsp_treasury
   ```

2. **Create a `.env` file** in the project root with your credentials:
   ```
   WRDS_USERNAME=your_wrds_username
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the pipeline**
   ```bash
   doit
   ```

## Data Sources

- **CRSP Treasury Database** (via WRDS): Historical Treasury bond prices, yields, and characteristics
- **TreasuryDirect.gov**: Treasury auction data with bid-to-cover ratios, SOMA participation, and more

## Configuration

The pipeline uses environment variables for configuration. Create a `.env` file based on `.env.example`:

```
WRDS_USERNAME=your_wrds_username
```

## Requirements

- Python 3.10+
- WRDS account (for CRSP data access)
- See `requirements.txt` for Python package dependencies

## Academic References

### Primary Paper

- **Fama and French (1993)** - "Common risk factors in the returns on stocks and bonds"
  - Journal of Financial Economics
  - Uses Treasury returns for TERM factor construction

### Key Features

- On-the-run/off-the-run status calculated from TreasuryDirect auction data
- Maturity-sorted portfolios for term structure analysis
