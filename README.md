# 🧪 Conconi Test Threshold Estimation
This project automates the estimation of aerobic and anaerobic thresholds using heart rate and lactate data from Conconi tests. It processes multiple athlete datasets, fits piecewise linear models, and compares threshold estimates across methods.

## 📚 Dataset Source
This project uses data from the open-access repository:

**Graded Incremental Test Data (Cycling, Running, Kayaking, Rowing) Zenodo**

DOI: 10.5281/zenodo.6325734 

Creators: Bernard Donne, Neil Fleming, Garry Campbell, Tomás Ward, David Crampton, Nick Mahony

### Dataset Overview
835 anonymized graded exercise test files:

* 285 cycling

* 266 rowing/kayaking

* 284 running

Each file includes:

* Test data: HR, VO₂, lactate across exercise intensities

* Anthropometric data: age, gender, height, body mass, BMI, skinfolds, % body fat, lean mass

* Haematological data: Hb, Hct, RBC, WBC

* Derived endurance indices

Tests were conducted at the Human Performance Laboratory, School of Medicine, Trinity College Dublin.

## 📦 Methods

* Piecewise linear fitting (PWLF)

* Automatic threshold detection for HR and lactate signals

* Dual-axis plots for HR and lactate curves

* Aggregated metrics across all athletes


## 📊 Output
PNG plots per athlete showing HR and lactate thresholds

Aggregated metrics:

MAE, MDAE, ME, MDE, MAPE, MdAPE, MdPE and MdPE for speed, HR, and pace differences between methods


## 🛠 Dependencies
numpy, pandas, matplotlib, pwlf, scipy, tabulate
