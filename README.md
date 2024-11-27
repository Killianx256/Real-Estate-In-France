# 🏠 Real Estate in France - Data Analysis and Visualization Platform

## 📝 Project Overview

**Real Estate in France** is a dynamic platform for analyzing and visualizing real estate transactions in France, using data from the **DVF (Demandes de Valeurs Foncières)** dataset. It provides tools to clean, explore, and interpret real estate trends over the last five years, delivering insights into pricing, transaction volume, and market dynamics.

---

## 🔑 Key Features

### 📊 Data Analysis
- **Comprehensive Analysis**:
  - Price per square meter by department, city, or region.
  - Comparisons of property types (houses vs. apartments).
  - Examination of regional trends and pricing differences.
- **Year-on-Year Comparisons**:
  - Analyze trends before and after COVID-19.
  - Compare transaction volumes and prices across years.

### 🗺️ Visualizations
- **Interactive Maps**:
  - Choropleth maps showing regional or departmental price variations.
  - Interactive tools for exploring transaction locations.
- **Trend Graphs**:
  - Price evolution over time.
  - Comparative graphs based on property types and regions.

### 💻 Web Application (Django)
- **Dynamic Interface**:
  - Generate visualizations based on user-selected filters (city, year, property type, etc.).
- **Responsive Design**:
  - Fully responsive for seamless use across all devices.

### 🔍 Data Integration
- **External Data Sources**:
  - Combine DVF data with demographic or economic datasets (e.g., from INSEE) for richer insights.

---

## ⚙️ Technologies Used

- **Backend**: 
  - Python (Pandas, Django).
- **Frontend**: 
  - HTML, CSS, JavaScript, Bootstrap.
- **Visualization**: 
  - Matplotlib, Plotly, Folium.
- **Mapping Tools**: 
  - GeoJSON, Leaflet.js.
- **Data Sources**:
  - [DVF Dataset](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/)
  - [GeoJSON France](https://france-geojson.gregoiredavid.fr/)

---

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Killianx256/Real-Estate-In-France.git
   cd Real-Estate-In-France
