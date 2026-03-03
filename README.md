# Tel Aviv Siren Resilience Analysis (Survival Study)

### **Project Overview**
In this project, I analyze the duration of "silence" in Tel Aviv between rocket sirens. My goal is to understand urban resilience by calculating how many hours of quiet a resident can expect after an alarm occurs.

### **Methodology**
Instead of just counting the number of alarms, I use the **Kaplan-Meier Estimator**. This is a statistical model usually used in medical research to measure survival probability. In this study:
* **The "Event"** is a siren.
* **The "Survival Time"** is the number of hours of silence between sirens.

### **Data Source**
I used the public dataset of alarms in Israel. The analysis focus specifically on 4 main districts of Tel Aviv:
1. **South & Jaffa**
2. **City Center**
3. **East**
4. **North** (Across the Yarkon river)

### **Key Features**
* **Detailed Grid Charts:** Visualization of silence probability over a 48-hour window.
* **KM Median Calculation:** Finding the exact hour when the probability of silence drops to 50%.
* **District Comparison:** A summary table to compare which areas are more resilient.

### **How to use**
1. Open the `Kaplan-Meier Model Tel Aviv Rocket Alerts.ipynb` file to see the code and graphs.
2. The code is organized into 3 sections: Calculations, Visualization, and Final Summary.

---
**Author:** Alex Tsiris  
**Field:** Industrial Engineering and Management.
