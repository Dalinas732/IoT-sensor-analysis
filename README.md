# 🏢 IoT Building Analytics & Occupancy Dashboard  

This project analyzes **temperature regulation** and **occupancy trends** in smart buildings using IoT sensor data. The work blends exploratory data analysis, metric development, and dashboard prototyping to produce insights that can inform energy efficiency, comfort, and space utilization strategies.  

---

## 🚀 Project Overview  

The dataset consisted of **time-series temperature and occupancy records** from building IoT systems. These records included setpoint values, zone temperature sensors, and occupancy modes, along with multiple types of occupancy sensors such as entry/exit counters, binary detectors, and people-count sensors.  

Key challenges addressed in the analysis included:  

- **Data Quality Issues** — Time-series data contained missing values, requiring careful alignment and interpolation to enable reliable analysis.  
- **Temperature Performance** — Explored how well building devices maintained setpoint conditions across different occupancy modes, covering hourly fluctuations over multiple days.  
- **Responsiveness** — Measured how quickly systems adjusted from unoccupied to occupied states, highlighting the dynamics of reaching thermal setpoints.  
- **Occupancy Integration** — Developed a **unified occupancy metric** that reconciled data across heterogeneous sensor types, enabling consistent comparisons between spaces.  
- **Dashboarding & Communication** — Designed a prototype dashboard to summarize occupancy patterns at both the **building** and **space** levels, with supporting slides tailored for stakeholders.  

---

## 📂 Repository Structure  

### `temp_sensors/`  
- EDA notebooks analyzing temperature sensor data  
- Organized per sensor for clarity  
- Findings summarized in slides - summary_temp_sensors.pptx

### `occupancy/`  
- EDA and construction of unified occupancy metric  
- `analysis_scratchwork.ipynb` — Full analysis behind dashboard  
- `occ_building/` & `occ_spaces/` — Separate building-level and space-level analyses  
- `new_metric.ipynb` — Dataset creation with the unified metric  
- **Slides:**  
  - `Dashboard.pptx` — Visual summary of findings  
  - `Summary_cleaning_data.pptx` — Methodology for unified metric  
---

## 📊 Deliverables  

- **Notebooks** — Complete exploratory analysis and metric construction  
- **Slides** — Executive summaries for stakeholders  
- **Dashboard Prototype** — Visual analytics for comparing occupancy across spaces and buildings  

---

## 🔧 Tools & Techniques  

- **Python** — Pandas, NumPy, Plotly, Matplotlib/Seaborn  
- **Jupyter Notebooks** — Iterative analysis and visualization  
- **Parquet Datasets** — Efficient time-series and occupancy data storage  
- **Presentation Slides** — Communicating insights to non-technical audiences  

---

## 📈 Key Outcomes  

- Quantified how well building systems maintained **temperature setpoints** across occupancy modes.  
- Assessed **time-to-setpoint responsiveness** after transitions to occupied states.  
- Created a **unified occupancy metric** for heterogeneous sensor streams.  
- Produced both **technical deep-dives** and **stakeholder-ready dashboards/slides** for multi-level communication.  
