# 🚢 Titanic Survival EDA – Simple Visual Story

This repository contains a beginner-friendly Exploratory Data Analysis (EDA) of the classic **Titanic dataset**.  
Using only **simple plots** (bar charts, histograms, boxplots, violin plots), the project explores:

- Who survived 🎯  
- How **class, gender, age, family, fare, and port** affected survival  
:contentReference[oaicite:0]{index=0}  

---

## 📂 Project Goal

Before jumping into ML models, this project focuses on **understanding patterns behind survival**:

- Passenger Class (1st / 2nd / 3rd)  
- Gender & Age distribution  
- Family size & travel type (Solo vs Family)  
- Fare differences (economic status)  
- Embarkation Port (C / Q / S)  
- Groups like **children, adults, and seniors**  

The main aim is to identify the **strongest survival predictors** and see how **social class, demographics, and travel patterns** shaped the outcome. :contentReference[oaicite:1]{index=1}  

---

## 🎯 Analysis Agenda

The EDA is structured around these questions: :contentReference[oaicite:2]{index=2}  

1. **Overall Survival Rate** – How many survived vs. did not survive?  
2. **Gender Impact** – Did females survive more than males?  
3. **Class Influence (Pclass)** – Which class had the highest survival rate?  
4. **Age Effect** – How did survival vary among children, adults, and seniors?  
5. **Solo vs Family Travel** – Did family groups have better chances than solo travelers?  
6. **Fare Influence** – Did higher ticket fare relate to higher survival?  
7. **Port of Embarkation** – Did survival and fare patterns change by port (C/Q/S)?  

---

## 📊 Visualizations (All Simple Plots)

The notebook uses **clean, simple plots** suitable for beginners:

- Bar chart – **Total Survived vs Not Survived**
- Bar chart – **Survival by Gender**
- Bar chart – **Survival Rate by Passenger Class**
- Histogram – **Age Distribution (Children, Adults, Seniors)**
- Bar / Count Plot – **Solo vs Family Travellers**
- Boxplot – **Fare Distribution by Class** :contentReference[oaicite:3]{index=3}  
- Violin plot – **Fare by Embarked Port (C/Q/S)** :contentReference[oaicite:4]{index=4}  

No complex dashboards, just **clear plots** that tell a story.

---

## 🔍 Key Observations (Short & Simple)

- **Age Distribution**  
  - Adults form the largest group.  
  - Children are fewer, seniors are very few. :contentReference[oaicite:5]{index=5}  

- **Class & Survival**  
  - 1st class shows the **highest survival share**.  
  - 2nd class has moderate survival.  
  - 3rd class has the **lowest survival percentage**. :contentReference[oaicite:6]{index=6}  

- **Fare & Class**  
  - 1st class passengers paid the highest fares.  
  - 3rd class has the lowest and tightest fare range. :contentReference[oaicite:7]{index=7}  

- **Fare & Embarkation Port**  
  - Port **C** shows the highest fare variation.  
  - Port **S** mostly has low-fare passengers.  
  - Port **Q** has limited variation and mostly low fares. :contentReference[oaicite:8]{index=8}  

(Additional notes on **gender** and **solo vs family** survival are explored visually in the notebook.)

---

## 🧾 Files in This Repo

- `Data Cleaning.ipynb` – Main Jupyter Notebook with full EDA
- `Visuallization.ipynb` – Main Jupyter Notebook with full Visuallization
- `Titanic.pptx` – Presentation summarizing insights and visual story  
- `README.md` – You’re here 🙂

---

## 🛠 Tech Stack

- **Language:** Python  
- **Core Libraries:**  
  - `pandas` – data handling  
  - `numpy` – numerical operations  
  - `matplotlib` / `seaborn` – visualizations  
- **Environment:** Jupyter Notebook / VS Code

---
