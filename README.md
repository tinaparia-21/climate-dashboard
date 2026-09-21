# 🌍 Climate Change Awareness Portal

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://climate-change-awareness-dashboard.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

An interactive Streamlit analytics platform designed to explore global carbon emissions, energy fuel mix dynamics, per capita footprints, and climate equity across nations.

---

## 📌 Key Features

- **📊 Executive Summary:** High-level overview of global carbon emissions, key metrics, and historical milestones.
- **📈 Country Trends:** Interactive tracking of historical emission trajectories from 1950 to 2024.
- **🗺️ Global Map:** Spatial distribution and global heatmaps highlighting top emitting nations.
- **🔌 Fuel Breakdown:** Detailed breakdown across fossil fuel sources including Coal, Oil, Gas, Cement, and Flaring.
- **⚖️ Equity & Per Capita:** Comparative analysis of per capita carbon footprints and trade-adjusted consumption emissions.
- **💡 Take Action & Quiz:** Interactive climate literacy quiz paired with actionable sustainability recommendations. User responses and feedback are captured dynamically via Google Sheets integration.
- **📁 Data Explorer:** Filterable dataset interface for inspecting, searching, and exporting raw data.
- **⚙️ Dynamic Filters:** Global sidebar controls enabling real-time filtering across all dashboard pages by year range and country.

---

## 🛠️ Tech Stack & Architecture

- **Frontend & App Framework:** [Streamlit](https://streamlit.io/)
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Plotly Express & Plotly Graph Objects
- **External Services & Data:**
  - **Dataset:** [Our World in Data (OWID) CO2 & Greenhouse Gas Dataset](https://github.com/owid/co2-data)
  - **Feedback Backend:** Google Sheets API (`gspread`) for live feedback and quiz response logging

---

## 🚀 Live Demo

Explore the deployed dashboard online:  
👉 **[Launch Climate Change Awareness Portal](https://climate-change-awareness-dashboard.streamlit.app/)**

---

## 💻 Getting Started

### Prerequisites

Ensure you have Python 3.8 or higher installed on your machine.

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/tinaparia-21/climate-dashboard.git](https://github.com/tinaparia-21/climate-dashboard.git)
   cd climate-dashboard
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

---

## 📂 Project Structure

```text
climate-dashboard/
│
├── .streamlit/          # Custom theme settings and server configurations
├── pages/               # Multi-page dashboard modules
├── app.py               # Main application entry point & router
├── requirements.txt     # Environment dependencies
├── .gitignore           # Git exclusion rules
└── README.md            # Project documentation
```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👩‍💻 Author

- **Tina Paria** — [@tinaparia-21](https://github.com/tinaparia-21)
