# 🚌 Optimizing Public Bus Network Scheduling

A demand-oriented **Linear & Mixed Integer Programming** model that optimizes urban bus scheduling across routes and time shifts, reducing operational cost while improving service quality.

> Operations Analytics Project — University of Niagara Falls (DAMO-610)

---

## 📌 Project Overview

Urban public bus systems often operate on fixed schedules that do not reflect real passenger demand. This leads to overcrowding during peak hours, idle buses during off-peak periods, high fuel and maintenance costs, and inconsistent service quality.

This project develops a **data-driven optimization framework** to dynamically assign buses across **93 routes and 4 daily shifts**, aligning supply with demand while respecting operational constraints.

---


## 🎯 Objectives

- Optimize bus allocation based on passenger demand  
- Minimize unnecessary trips and distance coverage  
- Improve fleet utilization during peak and off-peak periods  
- Maintain acceptable passenger wait times  
- Support scenario-based planning for demand fluctuations  

---


<img width="648" height="417" alt="Screenshot 2025-12-16 at 1 39 25 AM" src="https://github.com/user-attachments/assets/d6b4549b-a19f-436b-b5ca-7ec5e3480786" />

## 🧠 Methodology

The problem is formulated as a **Vehicle Scheduling Problem (VSP)** using Linear and Mixed Integer Programming.

**Key elements:**
- Decision variables represent trips per bus type, route, and shift  
- Objective function minimizes total trips (proxy for operational cost)  
- Constraints enforce:
  - Passenger demand satisfaction  
  - Fleet size and capacity limits  
  - Minimum service frequency  
  - Bus reuse across shifts  

The model is solved using **SCIP via Google OR-Tools**, enabling efficient handling of complex operational constraints.

---

## 🛠 Tools & Technologies

- Python  
- Google OR-Tools (SCIP Solver)  
- pandas, NumPy  
- Jupyter Notebook, Excel  
- Linear & Mixed Integer Programming  

---

## 📊 Key Performance Indicators (KPIs)

| Metric | Target | Achieved |
|------|------|------|
| Operating Cost Reduction | > 10% | **13.74%** |
| Distance Coverage Reduction | > 8% | **10.13%** |
| Peak-Hour Bus Utilization | 60–80% | **89.8%** |
| Monthly Cost Savings | > $35K | **$45K** |
| Daily Trips Reduction | — | **14.61%** |

---

## 🚀 Impact & Outcomes  
*(Inspired by real-world optimization case studies)*

### Operational Impact
- Reduced daily operating cost from **$1.10M → $0.95M**
- Eliminated ~8,000 km of unnecessary daily bus travel
- Improved peak-hour utilization from **overcrowded (116%) → optimal (89.8%)**
- Increased off-peak utilization from <20% to 42–51%

### Financial Impact
- **$45K monthly savings** from optimized scheduling
- Estimated **$1.2M annual fuel cost reduction**
- Lower maintenance costs due to reduced vehicle wear

### Service Quality Impact
- Maintained **30–60 minute wait times** across demand scenarios
- Reduced overcrowding during morning and evening peaks
- Enabled tiered service levels for weekdays vs weekends

---

## 🔍 Key Insights

### Optimal Service Level Trade-off
Analysis across 32 demand and wait-time scenarios showed that **30–60 minute service intervals** deliver the best balance between cost efficiency and passenger satisfaction.

### Fleet Rebalancing Effect
Smaller, lower-cost buses handled **87% of trips**, while high-capacity buses were reserved for high-demand peak routes. This correction alone accounted for most of the cost reduction.

### Distance & Sustainability Gains
Optimized scheduling reduced empty runs, cutting fuel consumption and lowering carbon emissions (≈21 tons CO₂/day).

---

## 👤 My Role

**Operations Analyst & Optimization Engineer**

- Led LP/MIP formulation and optimization design  
- Implemented solution in Python using SCIP solver  
- Designed demand synthesis and scenario analysis  
- Performed cost, utilization, and profitability analysis  
- Documented results and presented insights to stakeholders  

---


## 📁 Repository Structure

