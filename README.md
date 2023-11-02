Project title : Earthquake Prediction Model using Python

Overview :
This project aims to predict earthquakes using machine learning and Python. We utilize seismic data, feature engineering, and a predictive model to estimate the likelihood of earthquakes in specific regions.

 Table of Contents :
* Requirements
* Data
* Usage
* Result
* Steps taken
* Future Improvements
* Contribute
* Acknowledgment
* Contact
* Reference
* Conclusion

 Requirements :
- Python (>=3.6)
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib (you can install them using pip install -r requirements.txt)

 Data :
- The dataset we used here is database.csv file format.
- This dataset includes a record of the date, time, location, depth, magnitude, and source of every earthquake with a reported magnitude 5.5 or higher since 1965.

 Usage :
1. Clone this repository:bash git clone https://github.com/gkkarthika/FLAWLESS-.git
   
2. Navigate to the project directory:bash cd earthquake-prediction
   
3. Install the required dependencies:bash pip install -r requirements.txt
   
4. Run the prediction model:bash python earthquake_prediction.py
   
Model :
- Neural Network Machine learning model has been used for earthquake prediction.
- We collected and preprocessed earthquake data, ensuring it was in a format suitable for model training. This involved cleaning, transforming, and handling missing values.
- Our selected model was trained on the earthquake dataset and evaluated using appropriate metrics.

 Results :
- The results indicate promising potential for earthquake prediction. While the model may not predict every seismic event accurately, it shows significant progress in identifying patterns that lead to earthquakes, particularly in regions prone to tectonic activity.

Steps taken :
- Preprocessing of Dataset.
- Splitting the Datasets.
- Building ML models such as Linear Regression, Decision Tree and KNN.
- Visualization with Matplotlib and Seaborn.
- Prediction
- 
Future Improvements :
-This project is a stepping stone towards more robust earthquake prediction systems. As more data becomes available and machine learning techniques evolve, our model can be further refined to provide more accurate predictions. It has the potential to aid in disaster preparedness and risk mitigation efforts.

Acknowledgments :
- we used phython library.
- Kaggle Dataset.
- Dataset link : https://www.kaggle.com/datasets/usgs/earthquake-database

Contact :
- If you have any questions or need assistance, please contact, karthika.112110@sxcce.edu.in

Reference :
- https://www.ijrte.org/wp-content/uploads/papers/v8i6/F9110038620.pdf

Conclusion :
    our Earthquake Prediction Model project demonstrates the feasibility of using machine learning to forecast seismic events. While challenges remain, this work lays the foundation for continued research in the field of earthquake prediction and disaster risk reduction. As the model evolves, it has the potential to save lives and protect communities in earthquake-prone regions.
