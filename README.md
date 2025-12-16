# 🚌 Urban Bus Scheduling Optimization (Linear Programming)

An operations analytics project that optimizes **urban bus scheduling and allocation** using **Linear Programming**, reducing operational costs while improving service quality under fluctuating passenger demand.

> Academic project — DAMO-610: Operations Analytics  
> University of Niagara Falls, Canada

---

## 📌 Project Overview

Urban public transport systems often rely on **fixed bus schedules**, which fail to adapt to changing passenger demand throughout the day. This leads to:
- Overcrowded buses during peak hours
- Underutilized buses during off-peak hours
- Higher fuel, maintenance, and labor costs
- Poor passenger experience

This project models and solves the **bus allocation and scheduling problem** for a large urban bus network using **Linear Programming (LP)**.

The case study is based on **Anbessa City Bus Service Enterprise (ACBSE)** in Addis Ababa, operating across **93 routes and 4 daily shifts**.

---

## 🎯 Objectives

- Optimize bus allocation across routes and time shifts
- Match supply with passenger demand
- Reduce unnecessary trips and operational waste
- Improve overall service efficiency and reliability

---

## 🧠 Approach

### Problem Framing
- Fixed schedules do not reflect peak vs off-peak demand
- Mismatch causes congestion, idle capacity, and rising costs
- Scheduling problem modeled as a **resource allocation optimization**

### Solution
- Formulated a **Linear Programming model**
- Optimized number of trips per route per shift
- Considered:
  - Passenger demand
  - Fleet size limits
  - Bus capacities
  - Minimum service levels
  - Route balancing constraints

---

## 🧮 Optimization Model (High Level)

- **Decision Variables:**  
  Number of trips per bus type, route, and shift

- **Objective Function:**  
  Minimize total trips while meeting demand

- **Constraints Include:**  
  - Passenger demand satisfaction  
  - Fleet capacity limits  
  - Minimum trips per shift  
  - Non-negativity and route balancing  

---

## 🛠 Implementation

- **Programming Language:** Python  
- **Optimization Library:** Google OR-Tools  
- **Method:** Linear Programming (LP)

Steps:
1. Generate realistic demand per route and shift
2. Define decision variables for bus assignments
3. Apply operational and capacity constraints
4. Solve LP model
5. Analyze allocation results

---

## 📊 Key Results

- **Operational efficiency improved**
- **High-capacity buses prioritized** for peak demand
- **Trip redundancy minimized**
- **Demand evenly distributed across shifts**
- All operational constraints satisfied

**Notable Insight:**  
Low-capacity buses were used minimally, indicating potential for **fleet restructuring** or removal.

---

## 🔍 Key Insights

- Fixed scheduling causes systematic inefficiency in urban transport
- High-capacity vehicles deliver better utilization under demand variability
- Optimization models reveal **hidden waste** in legacy fleet structures
- LP provides a strong foundation for real-world transit decision-making

---

## 🚀 Future Extensions

- Real-time demand integration
- Multi-objective optimization (cost + passenger waiting time)
- Sustainability constraints (CO₂ emissions)
- Probabilistic demand handling
- Dynamic rescheduling during special events

---

## 📁 Repository Structure

