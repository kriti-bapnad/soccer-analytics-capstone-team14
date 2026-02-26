# Soccer Analytics Capstone

**Project (Trilemma Foundation): “Delivering Elite European Football (Soccer) Analytics”**

## Project Overview
This project aims to build an MIT-licensed, open-source analytics pipeline that predicts match outcomes before kickoff and calibrates live in-match analytics using historical performance. The system ingests public match event data to estimate a pre-match expected result from prior matches, which serves as a baseline for interpreting live metrics. The goal is to transform raw event data into historically grounded, context-aware insights rather than isolated match statistics.

> [!IMPORTANT]
> **License Notice**: The code in this repository is licensed under MIT. However, the data sources (StatsBomb and Polymarket) are not covered by the MIT license and have their own licensing terms. See the [Data Licensing](#data-licensing) section below.

### Data Available
This project uses public, event-level soccer data derived from the StatsBomb Open Data format, stored locally as Parquet files and processed using Polars.

Match Metadata :Includes competition, season, match date, home and away teams, and final score.

Event Data: Event-level records capturing every on-ball action in a match (e.g., passes, shots, duels, fouls) with timestamps, team and player identifiers, event type, pitch location, and outcome details.

Lineups: Match-specific player rosters with player IDs, team affiliations, and positions.

Prediction Market Data: Polymarket soccer data (market metadata, odds history, trades).

Our Team:
Nick Hellmer
Kriti Bapnad
Jeffrey Sonola
