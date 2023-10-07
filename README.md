# Project - BSC Mentorship 

# PCOS Detection Model. 
Polycystic ovary syndrome (PCOS) is a prevalent endocrine condition in females, particularly in reproductive-age women. 
PCOS is believed to affect 5-10% of women worldwide.Infertility, acne, amenorrhea or oligomenorrhea, hirsutism, insulin resistance, obesity, hyperandrogenism, and polycystic ovaries can all be signs of PCOS.
The link between PCOS and infertility has been thoroughly investigated, and it is considered to account for 40% of female infertility. 
Furthermore, it is a major cause of endometrial cancer. 
Aside from reproductive issues, PCOS is significantly linked to a variety of metabolic problems, including hepatic steatosis, glucose intolerance, dyslipidemia, type II diabetes and hypertension.

This project is aimed at building a machine learning model that is able predict whether a female patient has  PCOS or not.
Python progarmming language was used to build this model.
The data set used in building this model is available on kaggle: www.kaggle.com/prasoonkottarathil/polycystic-ovary-syndrome-pcos.
Started by importing the necessary libraries, reading the file and getting the data set ready.
Proceeded to performing some EDA and visualizing some outliers.
Though there were some outliers present in the dataset, they were not removed because the data set is small and removing them would further reduce the dataset and may cause overfitting. Hence, method robust to outliers was used.
The next step was model building. For the purpose of this project, the Random Forest Classifier algorithm was used.
GridSearchCV was employed for fine tuning the parameters for the model. The parameters selected yielded a 91% accuracy of the model.
