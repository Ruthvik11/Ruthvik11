## Hi there 👋

# Student Engagement Analyzer  
Predicting and Understanding Student Engagement in Online Courses  

## 🚀 Overview  
This project is an end-to-end solution to analyze and predict student engagement in online education platforms. Using an ETL pipeline and machine learning, it processes student interaction data, computes custom engagement scores, and identifies inactive students based on their learning patterns. The result? Actionable insights to improve course completion rates—now live and ready to explore!  

## 🔗 Live Demo  
Try it out here:https://studengage-frontend.onrender.com 
*See how engagement trends come to life!*  

## 🛠️ Tech Stack  
- **Languages**: Python  
- **Data Processing**: Pandas, NumPy  
- **Machine Learning**: Scikit-learn, RandomForestClassifier   
- **Database**: MongoDB Atlas
- **Visualization**: Seaborn, Matplotlib  
- **Backend**: FastAPI  
- **Deployment**: Render

## ✨ Features  
- **ETL Pipeline**: Extracts, transforms, and stores student interaction data.  
- **Engagement Score**: Custom formula based on quizzes, Timespentoncourse. numberofvideoswatched, and Quizescores  
-   
-  
- **Visual Insights**: Heatmaps, histograms, and boxplots of engagement trends.  
- **Prediction Ready**: Data prepped for ML models to forecast completion rates.  

## 📸 Preview  
![Engagement Heatmap]("C:\Users\Rithika\OneDrive\Documents\Pictures\Screenshots\Screenshot 2025-03-19 144048.png")  
*Caption: Visualizing student engagement patterns with a heatmap.*  

## ⚙️ How It Works  
1. **Data Extraction**: Pulls raw student interaction data .  
2. **Transformation**: Computes engagement scores and Engagement_level.  
3. **Storage**: Loads processed data into MongoDB for efficient querying.  
4. **Analysis**: Generates visualizations to uncover trends and outliers.  
5. **Prediction**: Prepares features for ML models to predict engagement outcomes.  

## 📦 Installation  
Want to run it locally? Here’s how:  
```bash
git clone https://github.com/Ruthvik11/student-engagement-analyzer.git  
cd student-engagement-analyzer  
pip install -r requirements.txt  
python main.py  
