# SHM of Offshore Structures Workshop

This repository contains a **Python notebook and supporting scripts** developed for the **SHM of Offshore Structures Workshop** on fatigue analysis. It is designed to familiarize users with:  

- **Integration with the OWI metadatabase**: Accessing geometric and fatigue-related information through a Python API.  
- **Material definitions**: Assigning material properties relevant for fatigue calculations.  
- **Strain data preprocessing**: Cleaning, filtering, and structuring raw strain measurements from sensors.  
- **Fatigue analysis workflows**: Computing cumulative fatigue damage, generating time series, and visualizing results.  

The notebook provides hands-on examples to help participants:  

- Fetch geometry and fatigue metadata directly from the OWI metadatabase.  
- Define and apply material properties for fatigue calculations.  
- Load and preprocess structural strain datasets.  
- Visualize cumulative fatigue damage with respect to time and operational conditions.  

This repository is intended for users interested in **offshore wind turbine structural health monitoring and fatigue analysis**, offering a practical introduction to combining experimental data with database-driven structural insights.

The workshop notebook can be opened on Binder 

## 🧩 Running on Binder

You can explore and run each notebook interactively using **Binder**, without installing anything locally.  
Each Binder link below will launch **classic Jupyter Notebook interface** in your browser and automatically open the corresponding notebook.

> 💡 It may take a few minutes for Binder to start the first time (it’s building the environment).  
> Once the environment is ready, notebooks will load instantly on subsequent launches.

---

### **1️⃣ Geometry & Resistance Metadata Exploration**

This notebook introduces the OWI Meta Database geometry and resistance parameters.

[![Launch Geometry & Resistance Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/1.Geometry_Resistance_OWIMetaDataBase.ipynb)

---

### **2️⃣ Load Processing**

This notebook covers preprocessing and conditioning of SCADA or simulation load data for fatigue analysis.

[![Launch Load Processing Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/2.Load_Processing.ipynb)


---

### **3️⃣ Fatigue Assessment**

This notebook performs the fatigue analysis using processed load data and stress cycle counting.

[![Launch Fatigue Assessment Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/3.Fatigue_Assessment.ipynb)


---

### 🧠 Notes

- All three notebooks share the same environment defined in `.binder/environment.yml`.  
- Data files (`.pkl`, `.gz`, etc.) stored in the `Notebooks/` folder are automatically available when launched on Binder.  
- You can also download the notebooks and run them locally if you prefer.

---

### ✅ Quick Reference

| Notebook | Purpose | Binder Link |
|-----------|----------|--------------|
| 1️⃣ 1.Geometry_Resistance_OWIMetaDataBase.ipynb | Explore geometry & resistance metadata | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/1.Geometry_Resistance_OWIMetaDataBase.ipynb) |
| 2️⃣ 2.Load_Processing.ipynb | Process SCADA/load data | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/2.Load_Processing.ipynb) |
| 3️⃣ 3.Fatigue_Assessment.ipynb | Perform fatigue analysis | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/3.Fatigue_Assessment.ipynb) |

---