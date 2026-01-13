🌲 **EcoType: Forest Cover Type Prediction Using Machine Learning**

📌 **Project Overview**  
> This project builds a **machine learning classification system** to predict the dominant **forest cover type** based on environmental and geographical features.
It uses the **Forest Cover Type Dataset** and compares multiple ML models before deploying the best-performing model using a **Streamlit web application**.
________________________________________

🌿 **Domain**  
Environmental Data & Geospatial Predictive Modeling
________________________________________

📂 **Dataset Information**  
**Source:** [Dataset Link](https://drive.google.com/file/d/1UzSSMGF9iqSb8YnSRXMt02v3uf9ZUOf6/view?usp=sharing)
**Dataset Size:** 145,891 rows × 13 columns
**Target Variable:** Cover_Type (7 forest cover classes)

**Feature Description**  
| Feature            |	Description       |
|-------------------------------|------------------------------------------|
|Elevation |	Height above sea level (meters)|
|Aspect	| Direction slope faces (degrees 0–360)|
|Slope	| Terrain steepness (degrees)|
|Horizontal_Distance_To_Hydrology |	Distance to nearest water source (meters)|
|Vertical_Distance_To_Hydrology |	Vertical distance to water source (meters)|
|Horizontal_Distance_To_Roadways	| Distance to nearest road (meters)|
|Hillshade_9am |	Illumination index at 9 AM (0–255)|
|Hillshade_Noon |	Illumination index at Noon (0–255)|
|Hillshade_3pm	| Illumination index at 3 PM (0–255)|
|Horizontal_Distance_To_Fire_Points	| Distance to nearest wildfire ignition point|
|Wilderness_Area |	Wilderness category (encoded)|
|Soil_Type |	Soil category (encoded)|
|Cover_Type |	Target forest cover class (1–7)|
________________________________________

🎯 **Project Objectives**  
 ✔ Data Cleaning & Preprocessing  
 ✔ Exploratory Data Analysis (EDA)  
 ✔ Feature Engineering  
 ✔ Handling Class Imbalance (Oversampling / SMOTE)  
 ✔ Model Training & Evaluation    
 ✔ Hyperparameter Tuning  
 ✔ Model Saving  
 ✔ Streamlit Web App Deployment  
________________________________________

⚙️ **Technologies Used**  
  •	Python 3.12  
  •	Pandas, NumPy  
  •	Scikit-learn, imbalanced-learn  
  •	XGBoost  
  •	Matplotlib, Seaborn  
  •	Streamlit  
  •	Joblib / Pickle  
________________________________________

🧠 **Machine Learning Models**  
  •	Logistic Regression  
  •	Decision Tree  
  •	Random Forest  
  •	K-Nearest Neighbors (KNN)  
  •	XGBoost  
**Evaluation Metrics:**  
  •	Accuracy Score  
  •	Confusion Matrix  
  •	Classification Report  
________________________________________

🖥️ **Streamlit App Features**  
  •	Manual input of environmental features  
  •	Real-time forest cover type prediction  
  •	Displays predicted class label  
  •	Scaled and encoded inputs handled automatically  
________________________________________

🌳 **Cover Type Classes**   
  **Label	Forest Type**  
    1. Spruce/Fir
    2.	Lodgepole Pine
    3.	Ponderosa Pine
    4.	Cottonwood/Willow
    5.	Aspen
    6.	Douglas-fir
    7.	Krummholz
________________________________________






