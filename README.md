# Data-Driven Urban Policy Benchmarking
## Singapore and South Korea

This project benchmarks how cities use **data-driven policy-making**
to transition from a present condition to measurable future outcomes.
The analysis focuses on observable before-and-after changes rather than
speculative or futuristic narratives.

---

## Case Study 1: Singapore — Solar PV Deployment

### Policy
- **Singapore Green Plan 2030** (launched 2021)
- Focuses on renewable energy adoption, especially solar photovoltaics.

### Data Source
- Singapore Open Data Portal (data.gov.sg)
- Dataset: Installed Solar Photovoltaic Capacity
- Access method: Public API (no file download required)

API endpoint:
https://data.gov.sg/api/action/datastore_search

### Before → After Logic
- **Before**: Gradual increase in installed solar capacity pre-2021
- **After**: Accelerated deployment following the Green Plan launch
- **Evidence**: Annual installed capacity (MWp) visualized over time

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

