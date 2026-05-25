# 🗳️ Tamil Nadu Assembly Election Analysis (2021 vs 2026)

## Decoding Tamil Nadu’s Political Realignment Through Data Storytelling & Interactive Analytics

An end-to-end political data analytics project analyzing the transformation of Tamil Nadu’s political landscape between the 2021 and 2026 Assembly Elections using:

- Python
- Pandas
- Plotly
- Power BI
- Claude AI
- Interactive HTML Dashboard

This project was developed as part of the **AtliQ Media Codebasics Resume Project Challenge**.

Live Dashboard Link : https://app.fabric.microsoft.com/view?r=eyJrIjoiZGIxZDQyZjEtMThlMS00MDQ1LWFiZTktYTM5YzVlM2E2MDg3IiwidCI6IjYyOTZhNGQzLTZiNjgtNGY3NC05ZWRhLWIxMDAzMzkyYzAxOCJ9

---

# 📌 Project Objective

The objective of this project is to uncover deeper political behavior patterns hidden inside election data by answering three major analytical questions.

## 1️⃣ The Geographic Story
How did political dominance shift across Tamil Nadu’s six major regions?

- Chennai Metro
- North
- Central
- Kongu
- Delta
- South

Which parties gained or lost ground between 2021 and 2026?

---

## 2️⃣ The Flip Story
How many constituencies changed winning parties between 2021 and 2026?

What political transfer patterns emerged?

---

## 3️⃣ The Vote Share Story
Where did TVK’s votes come from?

Did TVK gain support from:
- DMK voters?
- AIADMK voters?
- Both?
- Newly mobilized voters?

---

# 🚀 Project Highlights

✅ Constituency-Level Election Analysis  
✅ Regional Political Shift Tracking  
✅ Interactive Power BI Dashboard  
✅ Interactive HTML Dashboard  
✅ Sankey-Based Seat Transfer Visualization  
✅ Vote Share Transformation Analysis  
✅ Exploratory Data Analysis (EDA)  
✅ Political Storytelling Through Data Visualization

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|----------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Transformation |
| Plotly | Interactive Visualizations |
| Jupyter Notebook | Exploratory Data Analysis |
| Power BI | Interactive Dashboarding |
| HTML/CSS/JavaScript | Custom Web Dashboard |
| Streamlit | Web App Deployment |

---

# 📂 Project Structure

```bash
Tamil-Nadu-Election-Analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── eda_analysis.ipynb
│
├── powerbi/
│   ├── TamilNaduElectionDashboard.pbix
│
├── web_dashboard/
│   ├── index.html
│
│
├── presentation/
│   ├── Tamil_Nadu_Election_Analysis.pptx
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Exploratory Data Analysis (EDA)

Before building the dashboards, exploratory data analysis was performed to identify:
- political volatility
- vote share trends
- constituency-level shifts
- regional patterns
- electoral competitiveness

---

## 🔍 Key EDA Insights

### 🔹 Chennai Metro showed the highest political churn
Urban constituencies experienced the sharpest political shifts.

---

### 🔹 Legacy party vote concentration weakened
Both DMK and AIADMK experienced declining dominance across multiple regions.

---

### 🔹 Electoral competitiveness increased
Victory margins narrowed significantly in 2026.

---

### 🔹 TVK displayed balanced regional growth
Unlike region-specific parties, TVK expanded across multiple regions simultaneously.

---

# 📈 Power BI Dashboard

An interactive multi-page Power BI dashboard was developed to analyze:
- seat distribution
- vote share changes
- constituency flips
- regional political shifts
- party performance trends

---

## 📌 Dashboard Features

✅ Dynamic filtering  
✅ Region-wise analysis  
✅ Constituency-level drilldowns  
✅ Comparative election analysis  
✅ KPI tracking  
✅ Sankey-style political transfer analysis

---

## 📊 Dashboard Pages

### 1️⃣ Overview Dashboard
- Seat distribution
- Vote share summary
- KPI cards
- Regional analysis

---

### 2️⃣ Geographic Story
- Region-wise seat shifts
- Political stronghold analysis
- Regional flip rate

---

### 3️⃣ Vote Share Story
- State-wide vote share comparison
- Regional vote movement
- TVK vote source analysis

---

# 🌐 Interactive HTML Dashboard

To improve storytelling and presentation quality, a custom interactive web dashboard was also developed.

The HTML dashboard provides:
- modern UI/UX
- cinematic storytelling visuals
- interactive political analytics
- responsive visual design

---

## ✨ HTML Dashboard Features

✅ Animated KPI cards  
✅ Sankey diagrams  
✅ Responsive layout  
✅ Interactive charts  
✅ Political storytelling visuals  
✅ Dark-themed modern dashboard UI

---

# 🔄 Data Workflow

```text
Election Commission Data
        ↓
Python Data Cleaning
        ↓
EDA Analysis
        ↓
Feature Engineering
        ↓
Power BI Dashboard
        ↓
Interactive HTML Dashboard
        ↓
Political Insight Generation
```

---

# 📌 Key Findings

## 🗺️ Geographic Story
- Chennai Metro recorded the highest political churn
- TVK expanded aggressively across urban regions
- Delta region remained comparatively stable
- State-wide political realignment occurred

---

## 🔄 Flip Story
- 163 constituencies changed winning parties
- Flip rate reached nearly 70%
- Largest transfer occurred from DMK → TVK
- Elections became significantly more competitive

---

## 📊 Vote Share Story
- TVK secured nearly 35% vote share in its debut election
- Both DMK and AIADMK experienced double-digit decline
- TVK absorbed support from multiple voter blocs
- Newly mobilized voters contributed significantly

---

# 📸 Dashboard Screenshots

## 🏛️ Power BI Dashboard

<img width="1328" height="826" alt="image" src="https://github.com/user-attachments/assets/c4246f78-817e-40c6-b1ad-132ba3d76aea" />

---

## 🌐 HTML Dashboard

<img width="1730" height="958" alt="image" src="https://github.com/user-attachments/assets/3dbaaf0c-9db2-4fe6-8180-126d3b3bc9a9" />

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/Tamil-Nadu-Election-Analysis.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd Tamil-Nadu-Election-Analysis
```

---

# 🐍 Running the Python Notebook

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Open Notebook

Navigate to:

```bash
notebooks/eda_analysis.ipynb
```

Run all cells sequentially.

---

# 📊 Running the Power BI Dashboard

## Steps

1. Open Power BI Desktop  
2. Open:

```bash
powerbi/TamilNaduElectionDashboard.pbix
```

3. Refresh dataset if required

---

# 🌐 Running the HTML Dashboard

## Option 1 — Direct Open

Simply open:

```bash
web_dashboard/index.html
```

inside your browser.

---

## Option 2 — Run Using Live Server

If using VS Code:

### Install:
- Live Server Extension

### Then:
Right Click → `Open with Live Server`

---

# 📦 Required Python Libraries

```txt
pandas
numpy
plotly
matplotlib
seaborn
jupyter
streamlit
```

---

# 📌 Future Improvements

- Predictive election modeling
- Real-time election updates
- Candidate-level analysis
- Historical election trend analysis
- Mobile-responsive analytics app

---

# 🎥 Presentation & Storytelling

This project also includes:
- a cinematic presentation deck
- media-style storytelling
- interactive political analytics presentation

Designed specifically for:
## AtliQ Media Codebasics Resume Project Challenge

---

# 👨‍💻 Author

## Amit Kumar Mishra

### Connect With Me

- LinkedIn: https://www.linkedin.com/in/amitmishratheanalyst/
- Portfolio: https://amit-mishra-ai.github.io/

---

# ⭐ If You Found This Project Interesting

Feel free to:
- ⭐ Star the repository
- 🍴 Fork the project
- 📢 Share feedback

---

# 📜 License

This project is created for educational and portfolio purposes only.
