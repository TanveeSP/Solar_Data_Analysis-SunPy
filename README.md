# ☀️ Solar Data Analysis using SunPy – Astrophysics Project

## 📘 Problem Overview

This project is based on practical **Solar Physics Case Studies** using the **SunPy library**, which is widely used for solar data analysis.

The objective is to:

* Analyze **solar flare events** using observational data
* Work with real solar images to extract meaningful insights
* Apply computational techniques to study solar activity

The assignment is divided into two main parts inspired by standard SunPy case studies.

---

## 🛠️ Tech Stack

* Python 🐍
* SunPy ☀️
* Astropy
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📁 Project Structure

```id="k2x9vd"
📦 SunPy-Solar-Analysis
 ┣ 📜 README.md
 ┣ 📂 Notebooks
 ┃ ┣ 📓 A5P1.ipynb
 ┃ ┗ 📓 A5P2.ipynb
```

---

## 🌋 Part 1: Solar Flare Event Analysis (GOES Data)

This section focuses on querying and analyzing **solar flare events** using SunPy’s data access tools.

### 🔍 Key Objectives:

* Query solar flare events using **Fido search**
* Filter flares with intensity **greater than M1.0**
* Restrict results to the **first week of May 2023**
* Extract relevant event parameters

### 📘 What’s Done:

* Used SunPy’s HEK (Heliophysics Event Knowledgebase) interface
* Applied filters based on:

  * Time range
  * Event type (solar flares)
  * GOES classification (> M1.0)
* Extracted:

  * Start time
  * Peak time
  * End time
  * Flare class
  * Active region number

### 🌌 Outcome:

A clean dataset of significant solar flares is generated, enabling further analysis of **solar activity patterns**.

👉 **Run Notebook:**
[Open Part 1 Notebook](./Notebooks/A5P1.ipynb)

---

### 📡 Data Source (Solar Flare Events)

* Retrieved using SunPy Fido interface from the **Heliophysics Event Knowledgebase (HEK)**
* Instrument: GOES (Geostationary Operational Environmental Satellites)
* Time range: 1st – 8th May 2023
* Filter: GOES class > M1.0

🔗 Reference:
https://docs.sunpy.org/en/stable/guide/acquiring_data/hek.html

---

## 🌞 Part 2: Solar Image Analysis (Brightest Pixel Detection)

This section involves analyzing solar images to identify regions of maximum intensity.

### 🔍 Key Objectives:

* Load solar images from SunPy sample dataset
* Process image data using SunPy maps
* Identify the **brightest pixel location**
* Convert pixel coordinates into solar coordinate system
* Visualize the result on the image

### 📘 What’s Done:

* Loaded solar image using SunPy
* Computed maximum intensity value in the dataset
* Located corresponding pixel coordinates
* Converted pixel position to **helioprojective coordinates**
* Plotted the image with highlighted brightest region

### 🌌 Outcome:

This analysis helps identify **active regions on the Sun**, which are often linked to solar flares and magnetic activity.

👉 **Run Notebook:**
[Open Part 2 Notebook](./Notebooks/A5P2.ipynb)

---

### 📡 Data Source (Solar Image)

* Sample data provided by SunPy
* Dataset: AIA 193 Å
* Accessed via: `sunpy.data.sample.AIA_193_IMAGE`

🔗 Reference:
https://docs.sunpy.org/en/stable/generated/gallery/map/map_example.html

---

## 🚀 Key Learnings

* SunPy enables powerful access to real **solar observational data**
* Solar flares can be filtered and analyzed programmatically
* Image processing techniques help identify active solar regions
* Combining data querying and visualization provides deeper insights into solar physics

---

## 📌 Notes

* Data is dynamically fetched using SunPy (no local dataset required)
* Notebooks are modular and independently executable
* Standard astrophysical conventions are followed

---

## ⭐ Conclusion

This project demonstrates how **modern scientific Python tools like SunPy** can be used to analyze real solar data, bridging the gap between theoretical astrophysics and observational research.

---

## 👤 Author

* **Name:** Tanvee Sushama Paresh
* **GitHub:** [TanveeSP](https://github.com/TanveeSP)
