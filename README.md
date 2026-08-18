# 🌊 River Plastic Transport & Numerical Modeling Across Europe

A Python-based high-performance computing repository focused on predicting riverine macroplastic transport, retention rates, and coastal leakage probabilities across European river basins. This project implements advanced probabilistic frameworks inspired by the methodology of Meijer & van Emmerik (2021).

## 🚀 Analytical Features Implemented
1. **Numerical Hydrological Model:** Dynamically estimates plastic fate (retained vs. exported) based on river discharge rates ($m^3/s$) and in-stream vegetation trapping efficiency.
2. **Geospatial Probability Engine:** Calculates surface leakage probabilities using non-linear distance decay factors, annual rainfall statistics, and land-use roughness coefficients (Urban/Paved vs. Rural/Forest) with zero-to-one boundary constraints (`min/max` safety checks).

## 🛠️ Tech Stack & Architecture
- **Language:** Python 3.10+
- **Data Engineering:** Pandas & NumPy (Advanced array synthesis)
- **Data Visualization:** Matplotlib (Color-coded bar charts)

---
*Developed by [Dodi]* - Candidate for the EngD Engineering Doctorate in Forecasting Plastic Pollution Reduction.
