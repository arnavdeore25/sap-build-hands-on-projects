# 🏏 IPL Players Information

A mobile application built using **SAP Build Apps** to display cricket player information and franchise team information.

This project was developed as a hands-on practice project while learning **SAP BTP and SAP Build**.

---

## 📌 Project Overview

The application provides a simple interface to browse cricket players and view information about their respective franchise teams.

The original tutorial uses data from an S/4HANA Cloud system. Since an S/4HANA Cloud system was not available in my SAP BTP Student environment, I created and used a **synthetic cricket dataset** for this implementation.

---

## 🛠️ Technology Stack

- **SAP BTP**
- **SAP Build Apps**
- **SAP Build**
- **Excel / Synthetic Dataset**

---

## 📊 Data

The application uses a synthetic dataset containing player and franchise information.

The dataset includes fields such as:

- Player ID
- Player Name
- Team Name
- Team Short Name
- City
- Home Ground
- Founded Year
- Captain
- Coach
- Player Role
- Nationality
- Age
- Jersey Number
- Matches
- Runs
- Wickets
- Strike Rate
- Batting Average
- Highest Score
- Fifties
- Hundreds
- Status
- Team Titles
- Matches Played
- Matches Won
- Matches Lost
- Current Season Points

> **Note:** All player, franchise and statistical data used in this project is synthetic and created for educational purposes.

---

## 🏗️ Application Structure

```text
SAP Build Apps
       │
       ▼
Synthetic Cricket Dataset
       │
       ▼
Player Information
       │
       ├── Player Name
       ├── Team
       ├── Role
       ├── Nationality
       └── Statistics
       
       ▼
Franchise Information
       │
       ├── Team Name
       ├── City
       ├── Home Ground
       ├── Captain
       ├── Coach
       └── Team Statistics