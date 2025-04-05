# IPL Live Performance Dashboard  

## 📊 Project Overview  
A real-time analytics dashboard that tracks live IPL match data, evaluating batter and bowler performance metrics. Features an interactive points table ranking teams by strike rates and win/loss records, delivering data-driven insights for cricket enthusiasts.  

## 🎥 Project Demo Video
(Add this section right below the overview)
[Video Thumbnail](https://youtu.be/YuZidZN9qrY)
A quick walkthrough of the dashboard's live updates and features.

## 📸 Dashboard Screenshots
(Add this after the "How It Works" section)

**Live Match View**
(pic)Live Match Analytics
Real-time batting/bowling stats with run-rate comparison

**Points Table**
(pic)Team Standings
Interactive tournament rankings with filters

## 🛠️ Technical Implementation  

**Data Pipeline**  
- **Source**: Fetches live match data via Cricket API (RapidAPI)  
- **Processing**: Cleans and transforms JSON data using Power Query  
- **Metrics Calculated**:  
  - Batting: Runs, Strike Rate (e.g., 187.18), Boundaries (4s/6s)  
  - Bowling: Economy Rate (e.g., 5.8), Wickets  
  - Team Standings: Points, Net Run Rate (e.g., 1.49)  

**Visual Analytics**  
- Live match tracker with innings comparison  
- Player performance cards (Runs, Status)  
- Interactive points table with sorting  

**Tools Used**  
- Power BI (Visualization)  
- Power Query (Data Transformation)  
- DAX (Metrics Calculation)  

## ▶️ How It Works  
1. Connects to live cricket API  
2. Processes real-time match data  
3. Displays key metrics through interactive visuals  
4. Auto-updates during matches  
