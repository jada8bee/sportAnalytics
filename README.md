**player interface** https://stat-radar-hub-20385.lovable.app/
**recruit interface** https://scout-predict-dash.lovable.app
**admin interface** 


[README.md](https://github.com/user-attachments/files/22992350/README.md)
# 🧬 SportScout

## Predictive Performance Analysis

Based on an althlete's statistics and conditions, a Isolation Forest Regression model will analyze a transformed database to predict the varying performance of said althlete in different seasons.

## Predictive Recovery Analysis

Based on the severity of the condition, a Linear Regression model will predict the recovery time of althletes and the probability of future injuries.

## Predictive Player Conditioning

Based on recovery time analysis, a deterministic ML model will guide althletes on conditioning techniques to expedite the recovery process.

## Data

For the data, we used simulated synthetic CSV data and was inspired by the data statistics from basketball governed by Intercol in Jamaica.





[README (1).md](https://github.com/user-attachments/files/22992430/README.1.md)
# 🏀 Stat Radar Hub
**“Your Game. Your Data. Your Progress.”**
[![Status](https://img.shields.io/badge/status-active-brightgreen)]()
[![Build](https://img.shields.io/badge/build-passing-success)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![Made with](https://img.shields.io/badge/made%20with-Lovable.ai-ff69b4)]()
[![Tech Stack](https://img.shields.io/badge/frontend-React%2FTailwind-blue)]()

## 🌐 Live Demo
🔗 **Visit Here:** [https://stat-radar-hub-20385.lovable.app](https://stat-radar-hub-20385.lovable.app)

## 📘 Overview
**Stat Radar Hub** is a dynamic **basketball performance analytics web app** that allows players, coaches, and recruiters to visualize, compare, and analyze game statistics through **interactive dashboards** and **radar charts**.

The platform transforms traditional match data into visual insights—making it easier to track improvements, identify MVPs, and understand performance trends over time.

## 🚀 Features
✅ **Player Dashboard** – View personal game stats, averages, and seasonal progress  
✅ **Radar Graphs** – Visualize strengths and weaknesses in shooting, assists, steals, etc.  
✅ **Match Breakdown** – Access per-game data including MVP, top scorer, rebounds, assists, and fouls  
✅ **Admin Panel** – Edit player data, upload CSVs, or update live match results  
✅ **AI Performance Insights** – Automated suggestions on what to improve next game  
✅ **Injury Timeout Tracking** – Marks recovery periods based on medical input  
✅ **Responsive UI** – Designed for desktop, tablet, and mobile  
✅ **Firebase-based Real-Time Updates** – Stats update instantly across users  

## 🧩 Tech Stack
| Layer | Technologies Used |
|-------|-------------------|
| **Frontend** | React.js / Lovable / TailwindCSS / Recharts |
| **Backend** | Python (Flask / FastAPI) + Firebase Firestore |
| **Database** | Firebase Firestore (NoSQL) |
| **AI Analytics** | Python ML (Scikit-Learn – IsolationForest / RandomForest Regressor) |
| **Hosting** | Lovable.app Cloud |
| **Version Control** | GitHub + Git CLI |

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/stat-radar-hub.git
cd stat-radar-hub
```
### 2️⃣ Install Dependencies
```bash
npm install
```
### 3️⃣ Configure Environment
Create a `.env` file with:
```
FIREBASE_API_KEY=your_firebase_key
FIREBASE_PROJECT_ID=your_project_id
```
### 4️⃣ Run Locally
```bash
npm run dev
```
Open 👉 **http://localhost:3000**

## 📊 Usage Guide
1. **Log In** using your player or admin credentials.  
2. **Upload Match Data** (CSV or manual entry).  
3. **View Player Dashboards** with radar charts & trend lines.  
4. **Admins:** Approve or edit match stats in real-time.  
5. **AI Suggestions:** Check personalized improvement feedback.  

## 🧠 AI & Analytics
The app uses machine learning models (Isolation Forest + Regression Forest) to:  
- Predict MVP candidates  
- Estimate recovery time from injuries  
- Highlight weak performance areas (e.g., assists, steals, shooting efficiency)

## 🛠️ Contributing
1. Fork this repo  
2. Create a branch  
   ```bash
   git checkout -b feature/new-feature
   ```  
3. Commit changes  
   ```bash
   git commit -m "Add feature"
   ```  
4. Push & open a PR  

## 📜 License
This project is licensed under the **MIT License**.  
Feel free to use and modify for educational or portfolio purposes.

## 📈 Future Roadmap
- [ ] Player comparison mode  
- [ ] Automated highlight generator  
- [ ] API for mobile app integration  
- [ ] Dark/light theme toggle  
- [ ] Tournament dashboard  

## 👥 Team & Credits
**Developed By:**  
- Jahchrisi beadle (planning / Back and front End Engineer for the player user interface / prediction AI)
- jalen allen  (AI development / data base /back and front end engineer for recuit interface)
- andre morrison (back and front end for admin data base)
- daniel (login authorization)
- [Add teammates and roles here]  


## 🧾 Short README Version 
> **Stat Radar Hub** — Real-time basketball analytics platform built with **React**, **Firebase**, and **Python ML**.  
> Track player stats, visualize performance trends with radar graphs, and get AI-driven improvement tips.  
> 🌐 [stat-radar-hub-20385.lovable.app](https://stat-radar-hub-20385.lovable.app)




