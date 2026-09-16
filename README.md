# Farm to Fork Ledger

Interactive dashboard on the environmental footprint of 43 foods — greenhouse gas emissions, freshwater withdrawals, land use, and eutrophication, broken down across the farm-to-retail supply chain.

**[Live version](https://claude.ai/artifact/2kCwVJw7P6vRUi1DEvPAWC)** — or open `index.html` directly in a browser, no build step needed.

## What it shows

- Ranked bar chart of any of the four indicators, switchable per kg / per 1000 kcal / per 100g protein
- Seven-stage supply chain breakdown (land-use change → animal feed → farm → processing → transport → packaging → retail) for any product
- Plant-based vs. animal-based averages, compared side by side
- Full searchable, sortable data table

## Data

`data/Food_Production.csv` — Poore & Nemecek (2018), *Science*, via Our World in Data. 43 food products, 23 metrics per product.

## Stack

Single static HTML file (`index.html`) — vanilla JS, no build step, no dependencies beyond Google Fonts. The dataset is embedded inline as JSON.

---

Built as a first test of [Claude Code](https://claude.com/claude-code).
