# aviation-accident-analysis
Analysis of aviation accident data to provide business recommendations for aircraft safety.

---

## Business problem.
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

---

##  Project Overview
Aviation safety is a critical concern in the transportation industry. This project aims to analyze global aviation accident data to uncover trends, identify key risk factors, and provide data-driven insights. The analysis is conducted using **Python (Jupyter Notebook) for data cleaning and exploration**, **Tableau for visualization**, and **presentation materials** for reporting findings.

---

##  Project Structure
```
aviation-accident-analysis/
│── Aviation_analysis.ipynb       # Jupyter Notebook for data cleaning & analysis
│── README.md                     # Project documentation
│── LICENSE                        # Licensing information
│── cleaned_dataset.csv            # Cleaned dataset used for analysis
│
├── data/                          # Contains raw & uncleaned data
│   ├── aviation.csv               # Original dataset
│
├── Images/                        # Visualizations & plots from analysis
│   ├── accident_trends.png        # Example images
│   ├── aircraft_types.png         # More images...
│
├── Presentation/                   # Final Presentation slides (PDF, PPTX)
│   ├── Aviation_Analysis.pptx      # PowerPoint slides
│   ├── Aviation_Analysis.pdf     # PowerPoint slides in pdf  form
│
├── pdf formats/                    # Additional report formats
│  ├── Aviation_Report.pdf         # ionPDF vers
│   ├── Aviation_Analysis.pdf     # PowerPoint slides in pdf  form
│
```
---

##  Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** - Data cleaning, manipulation, and visualization
- **Jupyter Notebook** - Interactive analysis & coding
- **Tableau** - Advanced visualization and interactive dashboard
- **Git & GitHub** - Version control and collaboration
- **PowerPoint/PDF** - Presentation and report

---

## Dataset Information
- **Source:** Public aviation safety databases
- **File:** `aviation.csv`
- **Key Columns:**
  - `Date`: When the accident occurred
  - `Location`: Where it happened
  - `Aircraft Model`: Type of aircraft involved
  - `Fatalities`: Number of deaths
  - `Flight Phase`: Phase during which the accident occurred
  - `Cause Category`: The identified cause of the accident
  - `Operator`: Airline or organization operating the flight

---

## Installation & Setup
### 🔹 Clone the Repository
```bash
git clone https://github.com/lamohalicious/aviation-accident-analysis.git
cd aviation-accident-analysis
```

### 🔹 Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 🔹 Run the Jupyter Notebook
```bash
jupyter notebook
```
Then open `Aviation_analysis.ipynb` and execute the cells.

---

##  Tableau Dashboard
### 🔹 Interactive Visualizations
View the full Tableau **Aviation Accident Dashboard** here:  
👉 [Tableau Public Dashboard(https://public.tableau.com/app/profile/mohammed.abdi.farhan/viz/Aviation-analysis-dashboard/Aviation-Acccident-Analysis-Dashboard)

### 🔹 Tableau Visualizations
1. **Accidents by Country** - A world map representation of accident distribution
2. **Accidents Over Time** - Trends in aviation accidents by year
3. **Causes by Flight Phase** - Breakdown of causes during takeoff, cruise, landing, etc.
4. **Top Aircraft Models Involved** - Most accident-prone aircraft models


---

##  Key Insights
-  **Majority of accidents occur during landing & takeoff phases**
-  **Overall accidents have declined over the years**, but fatalities remain a concern
-  **Certain aircraft models appear more frequently in accidents**
-  **Accident frequency varies significantly by country & airline**

---

##  Future Improvements
- **Expand dataset** to include additional sources
- **Perform predictive modeling** to forecast accident probabilities
- **Improve Tableau dashboard** with more interactive features
- **Integrate Machine Learning** to analyze accident patterns

---

##  License
This project is licensed under the **MIT License**. See `LICENSE` for details.

---

##  Contributing
Contributions are welcome! Please follow these steps:
1. **Fork** the repository
2. **Create a new branch** (`feature-branch`)
3. **Commit changes** (`git commit -m "Added new analysis"`)
4. **Push to GitHub** (`git push origin feature-branch`)
5. **Create a Pull Request**

---

##  Contact
For questions, reach out via:
- **GitHub Issues**: [Issue Tracker](https://github.com/lamohalicious/aviation-accident-analysis/issues)
- **Email**: abdimohammedfarhan@gmail.com

---

 "Aviation safety is not just about statistics, it's about saving lives."

