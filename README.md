# Data-Driven Urban Policy Benchmarking
## Singapore and South Korea

This project benchmarks how cities use **data-driven policy-making**
to transition from a present condition to measurable future outcomes.
The analysis focuses on observable before-and-after changes rather than
speculative or futuristic narratives.

---

## Case Study 1: Singapore — Public Transport Utilisation

### Policy
- **Singapore Land Transport Master Plans (LTMPs)** (iterative; e.g. LTMP 2008, 2013, 2019)
- **Policy Goal**: To encourage a car-lite society by increasing public
  transport mode share, improving accessibility, and guiding long-term
  transport infrastructure investment using ridership data.

Rather than a single policy intervention, Singapore’s transport planning
relies on continuous, data-informed adjustments to rail expansion, bus
service planning, and demand management measures.


### Data Source
- Singapore Open Data Portal (data.gov.sg)
- Dataset: **Public Transport Utilisation – Average Public Transport Ridership**
- Publisher: Land Transport Authority (LTA)
- Time range: January 1995 – January 2024
- Last updated: 09 July 2025
- Access method: Public API (CKAN `datastore_search`)

API endpoint:
https://data.gov.sg/api/action/datastore_search

Dataset ID:
`d_75248cf2fbf340de6a746dc91ec9223c`


### Data Fields
- **Year**: Calendar year (YYYY)
- **Mode**: MRT, LRT, or Public Bus
- **Ridership**: Average daily ridership


### Before → After Logic
- **Before**: Lower and more uneven public transport ridership during
  earlier stages of rail network development (1990s–early 2000s).
- **After**: Sustained increases and shifts in ridership following major
  network expansions, service integration, and car-lite transport policies
  (2010s–2020s).
- **Evidence**: Longitudinal ridership trends across modes, enabling
  comparison of travel behavior before and after key planning phases.

This dataset enables a non-speculative evaluation of how transport policies
and infrastructure investments translate into measurable changes in
public transport usage over time.


---

## Case Study 2: South Korea — Seoul Food Waste Reduction

### Policy
- RFID-based Pay-As-You-Throw food waste policy (≈2013)
- Charges households based on measured food waste weight.

### Data Source
- Korea Public Data Portal (data.go.kr)
- Dataset must be downloaded manually due to access restrictions

Download link:
https://www.data.go.kr/en/data/15143917/fileData.do

### File Setup
- Rename the downloaded file to:
  `seoul_food_waste.csv`
- Place it in the repository root

### Before → After Logic
- **Before**: Higher annual food waste levels
- **After**: Sustained reduction following RFID enforcement
- **Evidence**: Aggregated annual waste volume plotted over time

---

## Methodology
- Python (Pandas, Matplotlib)
- Jupyter Notebook executed in VS Code
- No virtual environment required

---

## Purpose
These case studies serve as benchmarks for evaluating how
Jiading District could leverage data and policy together
to guide future urban planning decisions.

