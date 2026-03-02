# Data-Driven Urban Policy Benchmarking : Benchmarking Singapore and South Korea

![Teaser Figure](/assets/teaserfigure.png)

## Abstract

This project implements an interactive visualization framework that benchmarks data-driven urban governance practices in Singapore and South Korea to reveal how public datasets translate into measurable policy outcomes. Moving beyond aesthetic urban narratives, the prototype exposes the causal pathway between data collection, policy intervention, and observable social impact. Target audiences include policymakers, district leadership, urban planning students, and residents seeking greater transparency in civic decision-making.

The implementation features longitudinal dashboards, policy timeline overlays, interactive mode comparisons, and before–after inflection analysis using Singapore’s public transport ridership data and Gyeonggi Province’s RFID-based food waste reduction metrics. Users explore multi-year trends, district-level variation, and measurable behavioral shifts aligned with policy milestones.

By transforming governance into traceable, data-grounded narratives, this project demonstrates the educational and civic value of process transparency, fostering data literacy, accountability, and participatory urban planning through interactive visual storytelling.

---


## Disclaimer

This InfoVis project is for submission to INFOSCI 301 Data Visualization and Information Aesthetics, Spring 2026 at Duke Kunshan University.


## Acknowledgments

We thank Professor Luyao Zhang for guidance on community-based learning design, data governance, and visualization methodology.

We are grateful to our INFOSCI 301 peers for iterative critique and feedback on narrative framing and interaction design.

We acknowledge our community and institutional partners:

- Jiading District Urban Planning Exhibition Hall  
- Fengxian Waving Cube Sci-Fi Immersive Museum  
- Kunshan Museum of Chinese Opera Genres  

Industry contributors and open data platforms including Singapore Open Data Portal and Gyeonggi Open Data Portal enabled transparent benchmarking through publicly accessible datasets.

---

## Contribution to UN Sustainable Development Goals (SDGs)

**SDG 4 — Quality Education**  
Advances community-based learning through accessible data literacy tools and civic transparency frameworks.

**SDG 9 — Industry, Innovation and Infrastructure**  
Demonstrates innovative civic technology systems for transparent infrastructure governance.

**SDG 11 — Sustainable Cities and Communities**  
Promotes inclusive, participatory, and data-informed urban development.

**SDG 17 — Partnerships for the Goals**  
Establishes collaboration between students, policymakers, cultural institutions, and open-data providers.

---

## Accessibility

**GitHub Repository**  
https://github.com/Kmiriti/KPJ  

**Hugging Face Dataset**  
https://huggingface.co/datasets/KMiriti/KPJdataset/tree/main  

**Interactive Demo**  
https://preview--data-driven-policy-making.lovable.app/  

All datasets are publicly cited and linked. Analytical workflows are documented through Jupyter notebooks for reproducibility. The interface follows accessibility-conscious design principles including high-contrast compatibility, bilingual considerations, and transparent metadata disclosure aligned with SIGCHI accessibility guidance.

---

## Keywords

Information visualization; civic technology; urban governance; data transparency; geospatial storytelling; policy benchmarking; community-based learning; sustainable cities

---

# Case Study 1: Singapore -- Public Transport Utilisation

## Policy Context

Singapore’s Land Transport Master Plans (LTMP 2008, 2013, 2019) aim to transition toward a car-lite society by expanding rail infrastructure, optimizing bus networks, and integrating long-term ridership data into planning decisions.

---

## Data Source

- Platform: Singapore Open Data Portal (data.gov.sg)  
- Dataset: Public Transport Utilisation – Average Public Transport Ridership  
- Publisher: Land Transport Authority (LTA)  
- Time Range: January 1995 – January 2024  
- Access Method: Public API (CKAN `datastore_search`)  
- Dataset ID: `d_75248cf2fbf340de6a746dc91ec9223c`

API Endpoint:  
https://data.gov.sg/api/action/datastore_search  

---

## Before → After Policy Logic

**Before (1995–early 2000s)**  
Lower and uneven ridership levels during early network development.

**After (2010s–2020s)**  
Sustained ridership increases following MRT expansion and car-lite policies.

**Evidence**  
Longitudinal multi-mode trend analysis reveals measurable behavioral shifts aligned with planning phases.

---

## Singapore Dashboards

- Main Dashboard  
  https://kmiriti.github.io/KPJ/output/singapore_transport_main_dashboard.html  

- Mode Comparison Dashboard  
  https://kmiriti.github.io/KPJ/output/singapore_transport_mode_dashboard.html  

- Annual Trends Dashboard  
  https://kmiriti.github.io/KPJ/output/singapore_transport_annual_dashboard.html  

---

# Case Study 2: South Korea -- RFID-Based Food Waste Reduction

## Policy Context

RFID-based Volume-Based Food Waste Fee System (Pay-As-You-Throw)

**Policy Goal:**  
Reduce food waste by charging households based on exact disposal weight using RFID measurement systems.

**Timeline:**  
- Pilot (2013)  
- Expanded Rollout (2017)  
- Full Implementation (2019)

---

## Data Source

- Platform: Gyeonggi-do Open Data Portal (data.gg.go.kr)  
- Dataset: 음식물쓰레기발생 현황 (Food Waste Generation Status)  
- Publisher: Gyeonggi Provincial Government  
- Time Range: 2015–2024  
- Access: Open API (Service Key Required)

API Endpoint:  
https://openapi.gg.go.kr/Fodndrkwstoccur  

---

## Before → After Policy Logic

**Before (2015–2016)**  
Per-capita waste ≈ 0.38 kg/person/day.

**Implementation Phase (2017–2018)**  
Gradual decline as RFID infrastructure expanded.

**After (2019–2024)**  
Reduction to ≈ 0.25 kg/person/day (~25–30% decrease).

**Evidence**  
Clear inflection points aligned with policy milestones.

---

## Gyeonggi Dashboard

https://kmiriti.github.io/KPJ/output/gyeonggi_food_waste_dashboard.html  

---

# Embedded Multimedia Assets

## Teaser Video

<video src="assets/KPJ-Teaser_Video.mp4" controls width="100%"></video>

3-minute overview including:
- Scientific communication summary  
- Interactive dashboard walkthrough  
- Team acknowledgments  

---

## Final Poster (PDF Preview)

[![Poster Preview](assets/poster_thumbnail.png)](assets/A Data-Driven Urban Planning Visualization Framework for Jiading District Poster (78 x 200 cm).pdf )

---

# Data Governance & Reproducibility

This project adheres to FAIR principles (Findable, Accessible, Interoperable, Reusable).

- Publicly documented datasets  
- Transparent API metadata  
- Reproducible Jupyter notebooks  
- No personally identifiable information  
- Open-source repository structure  

---

# Educational & Social Impact

This framework advances process transparency in urban governance by explicitly linking:

**Data → Policy Decision → Behavioral Change → Measurable Outcome**

By transforming abstract planning into traceable evidence-based narratives, the project provides a replicable model for civic exhibitions, planning bureaus, and educational institutions seeking to increase public trust in data-driven decision-making.

It bridges technical rigor with narrative clarity — making policy legible, measurable, and participatory.