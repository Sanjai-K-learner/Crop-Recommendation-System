# 🌱 Climate Responsive Smart Farming

A smart farming assistant that provides personalized crop recommendations based on soil conditions, weather data, and location. The system also offers detailed budget estimations for selected crops to help farmers make informed decisions.

## Features

- 🌍 **Location-based Weather Analysis** using OpenWeather API
- 🌱 **Smart Crop Recommendations** powered by Machine Learning (Random Forest)
- 📊 **Top 3 Crop Suggestions** with suitability percentages
- 💰 **Detailed Budget Estimation** including costs, revenue, and profit projections
- 📱 **User-Friendly Interface** with multi-page navigation

## 🛠️ Technologies Used

- **Frontend**: Streamlit (Python)
- **Machine Learning**: Scikit-learn (Random Forest Classifier)
- **Weather API**: OpenWeatherMap
- **Data Processing**: Pandas, NumPy

## 📸 Screenshots
###                                                         Home Page
![Homepage](https://github.com/yourusername/AgriTech-Advisor/blob/main/screenshots/home.png)
###                                                         Input Page
![Input Page](https://github.com/yourusername/AgriTech-Advisor/blob/main/screenshots/input.png)
###                                                         Recommendations Page
![Recommendations](https://github.com/yourusername/AgriTech-Advisor/blob/main/screenshots/recommendations.png)
###                                                         Budget Page
![Budget](https://github.com/yourusername/AgriTech-Advisor/blob/main/screenshots/budget.png)

## 🏁 Getting Started

### 🔧 Requirements
- Python 3.8+
- Streamlit
- Required Python packages (install via requirements.txt)

### 🚀 Steps to Run the Project

1. **Clone the Repository**
     bash
     git clone https://github.com/yourusername/AgriTech-Advisor.git
     cd AgriTech-Advisor
   
2. **Install Dependencies**
    pip install -r requirements.txt
   
3. **Run the Application**
     streamlit run Home.py
   
4. **Access the Application**
    The application will automatically open in your default browser at           http://localhost:8501

### Project Structure

AgriTech-Advisor/
├── Home.py                 # Main application entry point
├── 1_📥_Input.py           # Farm input data collection
├── 2_🌱_Suggestions.py     # Crop recommendations display
├── 3_💰_Budget.py          # Budget estimation
├── Updated_Crop_data.csv   # Dataset for model training
└── requirements.txt        # Python dependencies


## 👨‍💻 Author
**Sanjai K — sanjaikannan2410@gmail.com**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/sanjai-k-5b1206299/) 

[![GitHub](https://img.shields.io/badge/-GitHub-100000?logo=github&logoColor=white&style=flat-square)](https://github.com/Sanjai-K-learner)

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 💡 Future Improvements
- Expand crop database with more varieties  
- Add seasonal planting recommendations  
- Include pest/disease warnings  
- Multi-language support for regional farmers   
- Integration with soil testing APIs  
- Historical price trends for crops  
- Government subsidy information  
