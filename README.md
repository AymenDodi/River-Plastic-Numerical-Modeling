# 🌊 River Plastic Transport & Numerical Modeling Across Europe

[Open In Colab] https://github.com/DuaaMusaad/River-Plastic-Numerical-Modeling/blob/main/River_Plastic_Numerical_Modeling.ipynb
A Python-based high-performance computing repository focused on predicting riverine macroplastic transport, retention rates, and coastal leakage probabilities across European river basins. This project implements advanced probabilistic frameworks inspired by the methodology of Meijer & van Emmerik (2021).

## 🚀 Analytical Features Implemented
1. **Numerical Hydrological Model:** Dynamically estimates plastic fate (retained vs. exported) based on river discharge rates ($m^3/s$) and in-stream vegetation trapping efficiency.
2. **Geospatial Probability Engine:** Calculates surface leakage probabilities using non-linear distance decay factors, annual rainfall statistics, and land-use roughness coefficients (Urban/Paved vs. Rural/Forest) with zero-to-one boundary constraints (`min/max` safety checks).

## 🛠️ Tech Stack & Architecture
- **Language:** Python 3.10+
- **Data Engineering:** Pandas & NumPy (Advanced array synthesis)
- **Data Visualization:** Matplotlib (Color-coded bar charts)

---
*Developed by [Duaa Ahmed Kassir]
## 📚 Scientific References & Formulations
The mathematical equations, decay factors, and hydrological probability constraints implemented in this simulation are strictly based on the following peer-reviewed literature:

- **Primary Study:** Meijer, L. J. J., van Emmerik, T., van der Ent, R., Schmidt, C., & Lebreton, L. (2021). *More than 1000 rivers account for 80% of global riverine plastic emissions into the ocean*. **Science Advances**, 7(18), eaaz5803. DOI: 10.1126/sciadv.aaz5803
- **Methodological Framework:** van Emmerik, T., et al. (2018). *A methodology to characterize riverine macroplastic emission into the ocean*. **Frontiers in Marine Science**, 5, 372.
