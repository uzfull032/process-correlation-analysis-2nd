# process-correlation-analysis-2nd
correlation works: between simulation and empirical outcomes in modified chambers

---

## 📄 Abstract

This study explores the relationship between pressure distribution and wafer coating uniformity in modified FOWLP bake chambers. Using correlation coefficients and R² values, we analyzed how structural changes, including baffle installation and inlet type (hole, slit, plain), influence coating quality. Strong correlations were found under optimized conditions, highlighting the importance of pressure control and chamber design. The findings provide data-driven insights for process improvement in semiconductor packaging.

---

## 📐 Correlation Analysis Formulas
referred to:

https://github.com/uzfull032/process-correlation-analysis-1st?tab=readme-ov-file#-mathematical-method

## 💡 Simulation and Empirical results

Simluation results:

https://github.com/uzfull032/FOWLP-Chamber-CFD-Study-2nd#%EF%B8%8F-representative-figures

Empirical results:

https://github.com/uzfull032/FOWLP-SixSigma-QualityStudy#-representative-figures

---
## 🖼 View Graphs

- ### Overview Correlation result in the modified chambers
<p align="left"><img width="834" height="623" alt="image" src="https://github.com/user-attachments/assets/6adc1c07-9387-4bc2-9f55-57aeac68f919" />



- ### Correlation result in non-baffle chambers
<p align="left">
  <img width="876" height="760" alt="image" src="https://github.com/user-attachments/assets/58154c2b-7185-493a-87fc-25a33748856f" />
  
  ### 📊 Table. R² Analysis for Each Condition in the Non-Baffle Chamber

| Graph | Condition          | Coating Thickness R² | Pressure Std. Dev. R² |
|-------|---------------------|-----------------------|------------------------|
| (a)   | Hole, 0.05 kPa      | 0.791                 | 0.730                  |
| (b)   | Hole, 0.15 kPa      | 0.803                 | 0.729                  |
| (c)   | Plain, 0.05 kPa     | 0.821                 | 0.809                  |
| (d)   | Plain, 0.15 kPa     | 0.950                 | 0.810                  |

<p/>


- ### Correlation result in with baffle chambers: velocity and pressure distribution and coating thickness
<p align="left">
  <img width="861" height="591" alt="image" src="https://github.com/user-attachments/assets/b7414f82-d795-4260-b341-c3eebe3b39e0" />

  ### 📊 Table. R² Analysis for Each Condition in the With-Baffle Chamber

| Graph | Condition           | Coating Thickness Std. Dev. R² | Velocity Std. Dev. R² |
|-------|----------------------|-------------------------------|------------------------|
| (a)   | Hole, 0.05 kPa       | 0.7041                        | 0.5826                 |
| (b)   | Hole, 0.15 kPa       | 0.8385                        | 0.5822                 |
| (c)   | Slit, 0.05 kPa       | 0.8716                        | 0.7309                 |
| (d)   | Slit, 0.15 kPa       | 0.8732                        | 0.7141                 |
| (e)   | Plain, 0.05 kPa      | 0.629                         | 0.7345                 |
| (f)   | Plain, 0.15 kPa      | 0.6305                        | 0.7271                 |

  <img width="861" height="591" alt="image" src="https://github.com/user-attachments/assets/3ccc1bc7-1387-48c5-bf2b-63fa6bb8f432" />
  
### 📊 Table. R² Analysis for Each Condition in the With-Baffle Chamber (Pressure Std. Dev.)

| Graph | Condition           | Coating Thickness Std. Dev. R² | Pressure Std. Dev. R² |
|-------|----------------------|-------------------------------|------------------------|
| (a)   | Hole, 0.05 kPa       | 0.7041                        | 0.508                  |
| (b)   | Hole, 0.15 kPa       | 0.8385                        | 0.5055                 |
| (c)   | Slit, 0.05 kPa       | 0.8716                        | 0.8396                 |
| (d)   | Slit, 0.15 kPa       | 0.8732                        | 0.8207                 |
| (e)   | Plain, 0.05 kPa      | 0.629                         | 0.5249                 |
| (f)   | Plain, 0.15 kPa      | 0.6305                        | 0.5216                 |
  
---

## ✅ Conclusion

The analysis confirmed that **coating thickness variation is highly correlated with flow pressure metrics across modified chamber types**. In particular, *the slit + baffle + 0.05 kPa configuration achieved the strongest correlation and coating consistency.* Structural modifications significantly influence the linearity of flow behavior. These results support the use of pressure-based control and design optimization to enhance wafer uniformity.

---
