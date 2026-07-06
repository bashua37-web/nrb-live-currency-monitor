# NRB Live Currency Monitor

A Python-based live currency monitor that fetches real-time foreign exchange rates 
from Nepal Rastra Bank's (NRB) official API and displays them with charts and conversion tools.

## Features

- Live exchange rate table for major currencies
- Currency conversion (NPR to foreign & foreign to NPR)
- Bar chart comparing exchange rates visually
- Historical trend visualization

## Technologies Used

- Python 3.x
- Jupyter Notebook
- `requests` — for fetching live data from NRB API
- `pandas` — for organizing and displaying data
- `matplotlib` — for charts and graphs

## Data Source

Live data fetched from the official Nepal Rastra Bank API:
https://www.nrb.org.np/api/forex/v1/rates

---

## How to Replicate This Project

### Step 1 — Install Python

Download and install Python from https://www.python.org/downloads/
Make sure to check **"Add Python to PATH"** during installation.

### Step 2 — Install Jupyter Notebook

Open your terminal or command prompt and run:

```bash
pip install notebook
```

### Step 3 — Install Required Libraries

```bash
pip install requests pandas matplotlib
```

### Step 4 — Clone This Repository

```bash
git clone https://github.com/bashua37-web/nrb-live-currency-monitor.git
```

Then navigate into the folder:

```bash
cd nrb-live-currency-monitor
```

### Step 5 — Open the Notebook

```bash
jupyter notebook
```

This will open Jupyter in your browser. Click on the `.ipynb` file to open it.

### Step 6 — Run the Code

Click **"Run All Cells"** from the top menu (Cell → Run All).

The program will:
1. Fetch live exchange rate data from the NRB API
2. Display a table of current rates
3. Show a bar chart comparing currencies
4. Allow you to convert between NPR and foreign currencies
5. Display a trend chart

> **Note:** You need an active internet connection for the live data to load.

---

## Project Context

Built as an economics assignment to demonstrate the practical use of live financial 
data APIs in Python, with a focus on Nepal's foreign exchange market.
