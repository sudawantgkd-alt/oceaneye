# oceaneye
🌊 OceanEye — AI-Powered Ocean Plastic Detection & Prediction

🚨 Problem Statement

Marine plastic pollution is one of the most critical environmental challenges today. Detecting plastic waste in oceans is extremely difficult because:

- Plastic is often smaller than a satellite pixel (sub-pixel level)
- It looks similar to algae, seaweed, and ocean foam
- Over time, biofouling (biological growth) hides plastic
- There is no system to predict where debris will move

This leads to inefficient and costly cleanup operations.



💡 Our Solution

OceanEye is an AI-powered ocean monitoring system that detects, tracks, and predicts marine plastic waste using satellite data and machine learning.

It provides:

- Accurate detection of plastic waste (even at sub-pixel level)
- Differentiation between plastic and natural ocean elements
- Prediction of debris movement using ocean currents and wind data
- A smart dashboard for decision-making and cleanup planning



🎯 One-Line Pitch

OceanEye is the Google Maps for ocean plastic — detecting what’s invisible, predicting where it goes, and guiding cleanup efforts.



⚙️ Key Features

🔍 Sub-Pixel Detection

- Uses Floating Debris Index (FDI)
- Detects plastic even if it covers a very small area

🧠 AI-Based Classification

- Deep learning models (CNN/Transformer)
- Differentiates plastic from algae, foam, and ships

⏳ Biofouling Detection

- Time-series analysis using LSTM
- Tracks how plastic changes over time

🌊 Trajectory Prediction

- Uses ocean current and wind datasets
- Predicts movement of debris for next 48–72 hours

🗺️ Interactive Dashboard

- Real-time plastic hotspots
- Cleanup priority zones
- Visual trajectory tracking



🛠️ Tech Stack

🛰️ Data Sources

- Sentinel-2 (ESA Copernicus)
- CMEMS Ocean Data
- ERA5 Wind Data

🧠 AI/ML

- PyTorch
- U-Net / SegFormer
- LSTM / Temporal Models
- Physics-Informed Neural Networks (PINNs)

🌐 Backend

- FastAPI
- PostgreSQL + PostGIS

🗺️ Frontend

- React
- Mapbox / Deck.gl

☁️ Tools & Infrastructure

- Docker
- Google Earth Engine



🏗️ System Architecture

Satellite Data → Data Processing → AI Detection → Time-Series Analysis → Trajectory Prediction → Dashboard


📊 Datasets Used

- MARIDA Dataset
- PlasticWatch
- MarineDebris-S2



🌍 Impact

- Reduces cleanup costs significantly
- Enables faster and smarter decision-making
- Helps governments and organizations monitor oceans efficiently



🔮 Future Scope

- Integration with radar-based satellite data (Sentinel-1)
- Mobile app for citizen reporting
- Real-time alert system for coastal threats



🏆 Why OceanEye?

- Combines AI + Satellite Data + Ocean Physics
- Solves a real-world global problem
- Provides actionable insights, not just raw data
