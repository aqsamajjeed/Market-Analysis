#  Data-Driven Product Management: Conducting a Market Analysis

##  Project Overview

This project explores global and national-level demand for digital fitness services by analyzing Google Trends data. As a product manager for a fitness studio, the goal was to identify trends, user interest, and growth opportunities for digital products like home workout platforms, gym services, and hybrid solutions.

---

##  Dataset Description

All CSV files are located in the `data/` directory.

### **1. workout.csv**
| Column               | Description                                                    |
|----------------------|----------------------------------------------------------------|
| `month`              | Month when the data was recorded                               |
| `workout_worldwide`  | Popularity index (0–100) of the keyword **'workout'**          |

### **2. three_keywords.csv**
| Column                   | Description                                                       |
|--------------------------|-------------------------------------------------------------------|
| `month`                  | Month of data collection                                          |
| `home_workout_worldwide`| Popularity index for **'home workout'** (0–100)                   |
| `gym_workout_worldwide` | Popularity index for **'gym workout'** (0–100)                    |
| `home_gym_worldwide`     | Popularity index for **'home gym'** (0–100)                       |

### **3. workout_geo.csv**
| Column                | Description                                               |
|------------------------|-----------------------------------------------------------|
| `country`              | Country name                                              |
| `workout_2018_2023`    | Popularity index for **'workout'** from 2018 to 2023     |

### **4. three_keywords_geo.csv**
| Column                        | Description                                                    |
|--------------------------------|----------------------------------------------------------------|
| `country`                      | Country name                                                   |
| `home_workout_2018_2023`       | Popularity index for **'home workout'** (2018–2023)            |
| `gym_workout_2018_2023`        | Popularity index for **'gym workout'** (2018–2023)             |
| `home_gym_2018_2023`           | Popularity index for **'home gym'** (2018–2023)                |

---

##  Key Insights

###  Global Peak of "Workout" Searches
-  **2020** saw the highest global search interest for the keyword **'workout'**, coinciding with the COVID-19 pandemic and global lockdowns.

###  Keyword Trend Analysis
-  The **most popular keyword during the COVID-19 pandemic (2020–2023)** was:  
  **`gym_workout_worldwide`**
  
-  The **most popular keyword now** (latest recorded month):  
  **`gym_workout_worldwide`**

### 🌍 Country-wise Demand

#### ➤ **Among United States, Australia, and Japan:**
- 🥇 **United States** has the highest interest in general **'workout'** searches.

#### ➤ **Between Philippines and Malaysia:**
- 🥇 **Philippines** shows a higher interest in **'home workouts'** compared to Malaysia.

---

## 🧠 Learning Outcomes

- Applied data-driven decision making for product strategy.
- Analyzed time-series search trends using Google Trends data.
- Identified market demand patterns based on geography and time.
- Visualized keyword popularity to support strategic business recommendations.
- Practiced filtering, aggregation, and peak-value detection using pandas.

---

## 🚀 How to Run

### 🛠️ Requirements

Install required Python libraries:
```bash
pip install pandas matplotlib
