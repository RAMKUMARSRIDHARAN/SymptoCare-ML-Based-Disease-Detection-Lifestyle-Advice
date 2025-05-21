# SymptoCare-ML-Based-Disease-Detection-Lifestyle-Advice


    SymptoCare is an intelligent health assistant web application built using Machine Learning and Streamlit. It helps users predict possible diseases based on selected symptoms and provides comprehensive health guidance including descriptions, precautions, medications, diets, and workout suggestions.

Project Overview:
    The primary goal of this project is to assist individuals in understanding potential health issues based on the symptoms they are experiencing. While not a replacement for medical consultation, SymptoCare offers educational and awareness tools to encourage healthier living and early symptom awareness.

Features
    Symptom-Based Disease Prediction using a trained Support Vector Machine (SVM) model.

    Detailed Disease Description to help users understand the condition.

    Precautionary Measures users can take to prevent the condition from worsening.

    Suggested Medications based on standard treatment practices.

    Diet Recommendations tailored to the predicted condition.

    Workout Guidance specific to the user's health situation.

Technologies Used: 
    
    Python

    Pandas, NumPy for data handling

    Scikit-learn for machine learning

    Streamlit for web app development

    Pickle for model serialization

    Custom datasets for disease descriptions, medications, diets, and workouts

Machine Learning Model:

    The disease prediction model is trained using a multi-label symptom dataset with Support Vector Machine (SVM), which has shown effective performance for this classification task.

Project Structure:

├── app.py                  # Streamlit application
├── svc.pkl                 # Trained ML model
├── description.csv         # Disease descriptions
├── medications.csv         # Medication suggestions
├── precautions_df.csv      # Preventive measures
├── diets.csv               # Dietary advice
├── workout_df.csv          # Workout guidance
├── symtoms_df.csv          # Symptom dataset


How to Run?

Clone the repository

Run the app:

streamlit run app.py
