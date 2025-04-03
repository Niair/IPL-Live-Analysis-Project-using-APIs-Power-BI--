# IPL Live Cricket Analysis Dashboard - Power BI Project 🏏📊

## 🌟 Project Overview
This **real-time IPL analytics dashboard** built with **Power BI** fetches live match data from **RapidAPI** to deliver dynamic visualizations of ongoing matches, player performances, and tournament standings. Designed for cricket analysts and fans, it provides instant insights with automated updates.

---

## 🚀 Key Features

### 📊 **Live Match Dashboard**
✔ **Real-time scorecards** for both innings with run rates  
✔ **Batting analytics**: Runs, 4s, 6s, strike rates (e.g., Buttler: 73 runs @ 187.18 SR)  
✔ **Bowling metrics**: Economy, wickets, wides (e.g., Bhuvi: 5.8 economy)  
✔ **Visual trends**: Required vs current run rate comparison  
✔ **Player spotlight**: Contributions via boundaries (14 fours, 11 sixes in sample data)  

### 🏆 **Tournament Intelligence**
✔ **Points table** with rankings (Punjab Kings leading in sample)  
✔ **Team performance**: Matches played, won/lost, NRR (Net Run Rate)  
✔ **Progress tracking**: Points accumulation (4 pts for top teams)  

### ⚡ **Tech Innovations**
✔ **API-powered**: Auto-refreshes data from RapidAPI  
✔ **Interactive filters**: Drill into teams/players (e.g., GT vs RCB focus)  
✔ **DAX measures**: Dynamic calculations (strike rates, NRR)  

---

## 🛠️ Technical Implementation

| Component          | Details                                                                 |
|--------------------|-------------------------------------------------------------------------|
| **Data Source**    | RapidAPI (Live IPL Match & Points Table APIs)                           |
| **Transformations**| Power Query M for data cleaning (e.g., parsing JSON responses)          |
| **Visualizations** | Custom cards, matrices, and trend lines in Power BI                      |
| **Calculations**   | DAX for metrics like `Strike Rate = (Runs/Balls)*100`                   |

---

## 📥 Setup Guide

1. **Prerequisites**:  
   - Power BI Desktop  
   - RapidAPI key (subscribe to cricket API)  

2. **Configuration**:  
   ```powerquery
   // Sample Power Query snippet for API connection
   Source = Json.Document(Web.Contents("https://cricket-api.p.rapidapi.com", [Headers=[#"X-RapidAPI-Key"="YOUR_KEY"]]))
   ```

3. **Usage**:  
   - Refresh dashboard to load live data  
   - Hover on visuals for tooltips (e.g., sixes contribution %)  

---

## 🎨 Dashboard Preview

![Live Match Page](https://via.placeholder.com/600x400?text=GT+vs+RCB+Live+Scores)  
*Live innings comparison with run rate charts*

![Points Table](https://via.placeholder.com/600x400?text=IPL+2025+Standings)  
*Sortable table with team rankings*

---

## 🔮 Roadmap

| Enhancement                          | Status  |
|--------------------------------------|---------|
| Win probability model                | Planned |
| Player head-to-head comparisons      | Next    |
| Mobile-responsive design             | Future  |

---

## 🤝 Contribute
**Got ideas?** Open an issue or submit a PR!  
👉 **Ways to contribute**:  
- Add new API data sources  
- Improve DAX measures (e.g., powerplay analysis)  
- Design enhancements  
