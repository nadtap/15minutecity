# 🏙️ 15-Minute City – Behavioral Data Analysis

## 📌 Overview

This project tests the *15-minute city* concept using **real mobility data** from Google Maps Timeline.

Instead of measuring *what is accessible*, it focuses on
👉 **what people actually do**.

---

## 🎯 Key Question

Do people really live locally — or just theoretically could?

---

## 🧠 Approach

* GPS trajectories (~400 users, Budapest)
* Home & workplace detection (clustering)
* 15-minute isochrones around home
* POI database (OpenStreetMap)
* **Localization index**:

  * share of activities within 15 minutes

---

## 📊 Main Findings

* ❌ Most people **do not follow** the 15-minute model
* 🏢 Work location is the **main constraint**
* 🛍️ People often **ignore nearby options** (“amenity bypass”)
* 📍 Local availability ≠ local behavior

---

## ⚙️ Tech Stack

* Python (pandas, geopandas, sklearn)
* Spatial analysis (OSM, isochrones)
* GPS data processing

---

## 🚀 Takeaway

> The 15-minute city is not just an urban design problem —
> it’s a **behavioral one**.

---

