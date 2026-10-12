# AquaLink 🌊
### GIS-Based Water Stress Decision Support Dashboard

AquaLink is a GIS-powered water stress decision-support platform designed to visualize regional water conditions, identify potential water-stressed areas, and support data-driven water resource planning. It combines interactive geographic maps, water-related datasets, and analytical visualizations in a unified dashboard.

## 🚀 Key Features

- **Interactive GIS Risk Map** — Explore geographical regions and visualize water-related risk patterns.
- **Water Stress Analysis** — Support identification of areas that may require attention based on available indicators.
- **Groundwater Monitoring** — Present groundwater-related information to help understand regional water availability.
- **Water Supply Analysis** — Organize and visualize water supply indicators.
- **Rainfall Analysis** — Explore rainfall data and its relationship to regional water conditions.
- **Historical Trends** — Support comparison of water-related indicators over time when historical data is available.
- **Hotspot Identification** — Highlight locations that may require further investigation or intervention.
- **Analytics Dashboard** — Present geographic data and key indicators through a centralized interface.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend user interface |
| Vite | Development server and build tooling |
| JavaScript / JSX | Application logic and components |
| CSS | Styling and responsive layouts |
| GeoJSON | Geographic boundary and spatial data |
| CSV / JavaScript datasets | Data storage and visualization inputs |

## 📁 Project Structure

```text
AquaLink_/
├── AquaLink/
│   └── backend/                 # Backend folder; implementation may be added here
└── aqualink-dashboard/
    ├── public/
    │   ├── aqualinkData.csv
    │   ├── districtData.js
    │   └── maharashtra.geojson
    ├── src/
    │   ├── components/
    │   │   ├── Dashboard.jsx
    │   │   ├── Header.jsx
    │   │   ├── KPICard.jsx
    │   │   ├── RiskMap.jsx
    │   │   └── Sidebar.jsx
    │   ├── pages/
    │   │   ├── Analytics.jsx
    │   │   ├── Dashboard.jsx
    │   │   ├── Forecast.jsx
    │   │   ├── MapPage.jsx
    │   │   └── Recommendations.jsx
    │   ├── utils/
    │   └── App.jsx
    ├── package.json
    ├── package-lock.json
    └── vite.config.js
```

## ⚙️ Getting Started

### Prerequisites

Install the following:

- [Node.js](https://nodejs.org/) — preferably an LTS version
- npm, included with Node.js
- Git

### 1. Clone the repository

```bash
git clone https://github.com/deesha-kalantri23/AquaLink_.git
cd AquaLink_
```

### 2. Navigate to the frontend

```bash
cd aqualink-dashboard
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL printed in your terminal, usually `http://localhost:5173`.

### 5. Create a production build

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 🗺️ How AquaLink Works

1. **Data Input:** Load the geographic and water-related datasets available to the application.
2. **Geographic Visualization:** Display supported regional data on interactive maps.
3. **Indicator Analysis:** Present water-related indicators and analytics using the available data.
4. **Risk Exploration:** Help users identify regions that may need further investigation.
5. **Decision Support:** Provide a consolidated view of geographic conditions to inform water-resource planning.

## 🎯 Intended Use

AquaLink is designed as a decision-support and visualization platform for:

- Water-resource researchers and analysts
- Urban and regional planners
- Environmental monitoring teams
- Government and public-sector stakeholders
- Students and researchers working on GIS applications

## 🔮 Future Scope

Potential future enhancements include:

- Integration of live groundwater, rainfall, and water-supply data sources
- Time-series forecasting and predictive analytics
- Improved water stress scoring based on validated indicators
- Automated alerts for emerging water-stress hotspots
- Role-based access for different stakeholders
- Backend APIs
