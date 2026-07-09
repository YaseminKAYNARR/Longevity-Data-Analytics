# Longevity-Data-Analytics: A Bio-Statistical & Clinical Categorization Approach

This repository contains a data analysis project that explores various lifestyle, dietary, and clinical factors influencing human life expectancy. Utilizing data science tools, these factors are mapped into distinct biological domains to reveal high-level trends in longevity.

## 🧬 Project Overview
Mainstream longevity research often looks at isolated habits. This project leverages a structured dataset (`LiveLongerData.csv`) to group 35 distinct lifespan-altering factors into 6 scientific taxonomies using an algorithmic categorization technique:
1. **Toxicology & Substance Use** (e.g., Smoking, Alcohol Abuse)
2. **Metabolism & Nutrition** (e.g., Obesity, Healthy Eating, Diet)
3. **Physiology & Genetics** (e.g., Genetics, Exercise, Sleep Patterns)
4. **Psychology & Mental Health** (e.g., Mental Illness, Meditation, Optimism)
5. **Socio-Environmental** (e.g., Marriage, Pets, Financial Status)
6. **Clinical & Pathology** (e.g., Healthcare Checks, Avoiding Major Diseases)

## 🛠️ Tech Stack & Architecture
* **Language:** Python 3
* **Data Manipulation:** `pandas`
* **Query Engine:** `sqlite3` (In-memory SQL analysis for high-performance indexing)
* **Visualization:** `matplotlib` & `seaborn`

## 📊 Key Insights & Visualization
The analytical pipeline automatically transforms raw textual factors, processes them through an algorithmic categorization function, runs SQL aggregates, and outputs a refined horizontal distribution chart.

* **Clinical & Pathology** behaviors and **Socio-Environmental** support show the highest positive correlation with years gained.
* **Psychology & Mental Health** features a heavy downward pull primarily driven by the severe clinical impact of untreated mental illnesses.

---
*Note: The underlying source code (.ipynb/.py files) and the raw `LiveLongerData.csv` dataset are kept private and confidential to secure proprietary data structures and algorithmic models.*
