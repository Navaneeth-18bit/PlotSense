# 🌍 PlotSense

**PlotSense** is an AI-powered smart land recommendation and analysis platform that helps buyers make informed land purchasing decisions by integrating **Machine Learning (ML)**, **Geographic Information Systems (GIS)**, and official geospatial data sources.

Unlike traditional land listing platforms that only display basic property information, PlotSense provides intelligent insights such as groundwater availability, nearby facilities, weather conditions, rainfall information, land suitability, and estimated market value to support data-driven land investment decisions.

---

## 📖 Project Overview

Purchasing land requires evaluating several factors beyond price and location. Buyers often spend significant time collecting information from multiple sources, making the process complex and prone to uninformed decisions.

PlotSense addresses this challenge by combining GIS technologies, machine learning models, and trusted public datasets to deliver comprehensive property analysis through a single platform.

---

## 🎯 Objectives

* Simplify the land buying process using AI.
* Provide intelligent land recommendations based on user preferences.
* Visualize properties using interactive GIS maps.
* Display groundwater, weather, rainfall, and nearby facilities.
* Estimate land prices using Machine Learning.
* Help buyers make transparent and informed investment decisions.

---

## ✨ Key Features

### 👤 User Management

* Buyer Registration & Login
* Seller Registration & Login
* Secure Authentication (JWT)

### 🏡 Property Management

* Seller Property Listing
* Property Images
* Property Details
* Property Search & Filtering

### 🗺 GIS Integration

* Interactive Map View
* Property Location Visualization
* District and Location Identification
* Nearby Facilities
* Groundwater Information
* Weather Information
* Rainfall Information

### 🤖 AI & Machine Learning

* Smart Land Recommendation
* Land Suitability Analysis
* Land Price Prediction *(Planned)*
* Investment Insights *(Future Enhancement)*

---

## 🛠 Technology Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* Axios
* React Leaflet

### Backend

* Node.js
* Express.js
* Prisma ORM
* JWT Authentication
* Multer

### Database

* PostgreSQL
* PostGIS

### Machine Learning

* Python
* FastAPI
* Scikit-learn
* Pandas
* NumPy
* Joblib

### GIS & Maps

* Leaflet
* OpenStreetMap
* PostGIS

---

## 🌐 External APIs

### Nearby Facilities

* Google Places API *(or OpenStreetMap Overpass API)*

### Weather & Rainfall

* Open-Meteo API

### Geocoding

* Nominatim (OpenStreetMap)

---

## 📂 Project Structure

```text
PlotSense/
│
├── frontend/
├── backend/
├── ml-service/
├── datasets/
├── docs/
├── architecture/
├── README.md
└── .gitignore
```

---

## ⚙️ Development Workflow

```
Requirement Analysis
        ↓
Environment Setup
        ↓
Database Design
        ↓
Backend Development
        ↓
Frontend Development
        ↓
GIS Integration
        ↓
Machine Learning
        ↓
Testing
        ↓
Deployment
```

---

## 📊 Data Sources

Current data sources include:

* Groundwater Dataset (CSV)
* Open-Meteo API (Weather & Rainfall)
* Nominatim API (Geocoding)
* Google Places API / OpenStreetMap Overpass API (Nearby Facilities)

Additional government GIS datasets may be integrated in future versions.

---

## 🚀 Future Enhancements

* Soil Quality Analysis
* Flood Risk Assessment
* Land Use/Land Cover Integration
* Investment Growth Prediction
* Satellite Imagery Integration
* Mobile Application
* Advanced Recommendation Engine

---

## 👨‍💻 Team

Developed as a Final Year Engineering Project.

---

## 📄 License

This project is developed for academic and research purposes.
