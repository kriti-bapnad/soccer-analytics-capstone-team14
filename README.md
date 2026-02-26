# Soccer Analytics Capstone

**Project (Trilemma Foundation): “Delivering Elite European Football (Soccer) Analytics”**

## Project Overview
This project aims to build an MIT-licensed, open-source analytics pipeline that predicts match outcomes before kickoff and calibrates live in-match analytics using historical performance. The system ingests public match event data to estimate a pre-match expected result from prior matches, which serves as a baseline for interpreting live metrics. The goal is to transform raw event data into historically grounded, context-aware insights rather than isolated match statistics.

> [!IMPORTANT]
> **License Notice**: The code in this repository is licensed under MIT. However, the data sources (StatsBomb and Polymarket) are not covered by the MIT license and have their own licensing terms. See the [Data Licensing](#data-licensing) section below.

### Polymarket Data Available
The following data is available in `data/Polymarket/` for analysis:
* `soccer_markets.parquet`: Core metadata for soccer markets (questions, slugs, end dates).
* `soccer_tokens.parquet`: Mapping of markets to specific outcome tokens (e.g., "Yes", "No", team names).
* `soccer_trades.parquet`: Granular, trade-by-trade execution data (price, size, timestamp).
* `soccer_odds_history.parquet`: Time-series odds (price history) reconstructed from order books.
* `soccer_event_stats.parquet`: Aggregated volume and market count per event.
* `soccer_summary.parquet`: High-level market summaries (trade counts, first/last trade).

Our Team:
Nick Hellmer
Kriti Bapnad
Jeffrey Sonola
