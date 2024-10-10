
# **📊 China Crime Scene Analysis**  

A comprehensive crime scene analysis project utilizing Python, data visualization, and machine learning techniques to extract insights from crime data in China. This repository includes a detailed analysis, visualizations, and predictive modeling based on a crime dataset.

---

## **📝 Project Overview**
This project aims to explore crime trends in China using a dataset of 1,000 crime reports, covering various aspects such as crime types, geographic distribution, demographic profiles, and temporal patterns. Additionally, machine learning algorithms are applied to predict crime types and uncover hidden patterns.

---

## **🔍 Analysis Components**

### **1. Exploratory Data Analysis (EDA)**
- **Crime Type Distribution**: Identifies the most frequent types of crime.
- **Geographical Crime Analysis**: Visualizes crime hotspots using GeoPandas.
- **Temporal Analysis**: Examines crime trends over time (monthly and daily).
- **Demographic Analysis**: Studies age profiles of victims and suspects.
  
### **2. Geographic Mapping**
- Visualizes crime distribution across Chinese provinces using latitude and longitude data.
- Heatmaps to identify crime hotspots in major cities.

### **3. Clustering and Pattern Recognition**
- **K-Means Clustering**: Groups locations with similar crime rates.
  
### **4. Predictive Modeling**
- A **Random Forest** classifier predicts crime types based on location, suspect age, and time of the crime.

---

## **💻 Key Features**
- **Data Preprocessing**: Handling missing values and formatting data for analysis.
- **Data Visualization**: Utilizes Python libraries such as Matplotlib, Seaborn, and GeoPandas for visual insights.
- **Predictive Analysis**: Implements machine learning models for crime prediction and clustering.
  
---

## **📂 Repository Structure**

```
📦 China-Crime-Scene-Analysis
│
├── 📁 data/                # Contains the dataset used for analysis
│   └── china_crime_data.xlsx
│
├── 📁 notebooks/           # Jupyter Notebooks for analysis and modeling
│   └── Crime_Scene_Analysis.ipynb
│
├── 📁 images/              # Contains images generated from analysis
│   └── crime_heatmap.png
│   └── age_distribution.png
│
├── 📄 README.md            # Project Documentation (This file)
│
├── 📄 requirements.txt     # Python packages required to run the analysis
│
└── 📄 LICENSE              # License for the project
```

---

## **🚀 How to Use**

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/china-crime-scene-analysis.git
cd china-crime-scene-analysis
```

### **2. Install Dependencies**
Make sure you have Python 3.7+ installed. Install the required Python packages using `pip`:

```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebook**
You can explore the analysis and run the code in the provided Jupyter Notebook:

```bash
jupyter notebook notebooks/Crime_Scene_Analysis.ipynb
```

---

## **📊 Dataset Overview**
The dataset contains 1,000 records of crime-related data with the following columns:
- **Crime_ID**: Unique identifier for each crime
- **Crime_Type**: Categories of crimes (Assault, Burglary, etc.)
- **Location**: City or region where the crime took place
- **Date & Time**: When the crime occurred
- **Victim_Age** and **Suspect_Age**: Demographics of the involved individuals
- **Weapon_Used**: Weapons used in the crime
- **Latitude** and **Longitude**: Coordinates for crime location

---

## **🔧 Technologies and Libraries**
- **Python**: Core programming language for the analysis
- **Pandas**: Data manipulation and preprocessing
- **Matplotlib** & **Seaborn**: For creating visualizations
- **GeoPandas**: For mapping geographic crime data
- **Scikit-learn**: For clustering and predictive modeling
- **Jupyter Notebook**: Interactive development and sharing environment

---

## **📈 Key Results**
- **Crime Hotspots**: Coastal cities like Shenzhen and Guangzhou are major crime hotspots.
- **Seasonal Trends**: Crime rates peak during winter months, particularly around holidays.
- **Demographic Insights**: Victims tend to be younger adults (20-40), while suspects span a wider age range.
- **Machine Learning**: A Random Forest classifier achieved an accuracy of 85% in predicting crime types.

---

## **📜 License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **💡 Future Work**
- Include socioeconomic data (income, unemployment) to explore correlations with crime.
- Enhance the predictive model using advanced deep learning techniques.

---

## **👨‍💻 Contributing**
Feel free to submit pull requests or raise issues if you find any bugs or have suggestions for improvements. Contributions are welcome!

---

## **📧 Contact**
If you have any questions or feedback, feel free to reach out at [vishrut225@gmail.com](mailto:vishrut225@gmail.com).

---

### **🌟 If you found this project helpful, please give it a star! 🌟**
