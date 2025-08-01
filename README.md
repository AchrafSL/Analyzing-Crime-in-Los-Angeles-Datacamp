# Analyzing Crime in Los Angeles

This project uses data manipulation to explore crime patterns in Los Angeles using a modified dataset from the LAPD. The goal is to identify time-based and demographic trends that can help inform resource allocation decisions. The analysis focuses on peak crime hours, nighttime crime locations, and victim age group trends. The project was completed using DataCamp’s Datalab environment.

## 🎯 Project Objectives

- Determine the **hour of the day** with the highest crime frequency
- Identify the **area with the most nighttime crime**
- Analyze crime distribution by **victim age group**

## 🗃️ Dataset Overview

The dataset used is [`crimes.csv`](./crimes.csv), based on publicly available LAPD data. Key columns include:

| Column         | Description                                     |
|----------------|-------------------------------------------------|
| `DR_NO`        | Official LAPD file number                      |
| `DATE OCC`     | Date of crime occurrence                        |
| `TIME OCC`     | Time of crime in 24-hour format                 |
| `AREA NAME`    | Name of LAPD geographic area                    |
| `Crm Cd Desc`  | Description of the crime                        |
| `Vict Age`     | Age of the victim                               |
| `Vict Sex`     | Gender of the victim                            |
| `Vict Descent` | Victim's racial or ethnic background            |
| `Weapon Desc`  | Description of weapon used (if applicable)      |
| `Status Desc`  | Status of the case                              |
| `LOCATION`     | Street address of the incident                  |

Derived columns:
- `Hour`: Extracted hour from `TIME OCC`
- `Period`: Time of day category (night, morning, afternoon, evening)
- `Age_group`: Victim age grouped into standard age brackets

## 🔍 Key Findings

- 🕛 **12 PM** was the peak hour for reported crimes
- 🌃 The **Central** LAPD area had the highest number of **nighttime** crimes
- 👥 The **26–34 age group** represented the largest share of victims

## 🛠️ Tools Used

- **Python**
- **pandas** for data manipulation
- **NumPy** for conditional logic
- **Matplotlib** / **seaborn** (optional, not visualized in final version)

## 📌 How to Use

1. Clone or download this repository
2. Open the notebook [`Analyzing_Crime_in_Los_Angeles.ipynb`](./Analyzing_Crime_in_Los_Angeles.ipynb) in Jupyter or a compatible notebook environment
3. Run the cells to reproduce the analysis
4. Modify filters to analyze other time periods, crime types, or demographics

## ✍️ Author

Project by **Achraf Salimi** — part of an ongoing journey to build and showcase data skills.
