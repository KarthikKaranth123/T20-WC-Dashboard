# 🏏 Cricket Team Selection Dashboard

## 📌 Project Overview
This project is a **Cricket Analytics Dashboard** built to analyze player performance and help in **optimal team selection**.  
The dashboard is based on **parameter scoping** criteria to select the best XI players capable of scoring and defending consistently.  

The project answers the question:  
> *“We don’t know the strengths and weaknesses of our opponents, but can we select the best 11 from this planet?”*

---

## 🎯 Objectives
- Select a team that can **score 180+ runs on average**.  
- Ensure the team can **defend 150+ runs on average**.  
- Provide an **interactive dashboard** to filter, compare, and select players based on performance metrics.  

---

## ⚙️ Features
- **Player Role Categorization**:
  - Openers
  - Anchors / Middle Order
  - Finishers
  - All-rounders
  - Specialist Fast Bowlers
- **Custom Filters** based on Batting & Bowling Stats (Avg, Strike Rate, Economy, Dot %).  
- **Performance Insights**: Boundary %, Batting Position, Balls Faced, Wickets, etc.  
- **Interactive Visualizations** for comparing players and identifying best fits.  

---

## 📊 Parameter Scoping

### 🔹 Openers
- Batting Avg > 30  
- Strike Rate > 140  
- Boundary % > 50  
- Batting Position < 4  

### 🔹 Anchors / Middle Order
- Batting Avg > 40  
- Strike Rate > 125  
- Avg. Balls Faced > 20  
- Batting Position > 2  

### 🔹 Finishers
- Batting Avg > 25  
- Strike Rate > 130  
- Avg. Balls Faced > 12  
- Batting Position > 4  
- Should have bowled ≥ 1 innings  

### 🔹 All-rounders
- Batting Avg > 15, Strike Rate > 140  
- Bowling Economy < 7, Strike Rate < 20  
- Batting Position > 4, Innings Bowled > 2  

### 🔹 Specialist Fast Bowlers
- Innings Bowled > 4  
- Bowling Economy < 7  
- Bowling Strike Rate < 16  
- Dot Ball % > 40  
- Bowling Average < 20  

---

## 🛠️ Tech Stack
- **Dashboard Tool**: Power BI / Tableau / SAP SAC (replace with yours)  
- **Data Processing**: Python (pandas, NumPy)  
- **Visualization**: matplotlib, seaborn (if used alongside BI tool)  
- **Dataset**: Cricket player statistics (batting & bowling records)  

---

## 📌 Future Scope
- Add **dynamic team builder** (auto-select XI based on filters).  
- Integrate with **live cricket APIs** for real-time selection.  
- Compare **historical match outcomes** with selected XI.  
