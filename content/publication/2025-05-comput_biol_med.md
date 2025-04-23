+++
title = "A data-driven personalized approach to predict blood glucose levels in type-1 diabetes patients exercising in free-living conditions"
date = "2025-05-01T00:00:01"
draft = false

authors = ["A Neumann", "Y Zghal", "MA Cremona", "A Hajji", "M Morin", "M Rekik"]
publication = "_Computers in Biology and Medicine_"
publication_short = "_Comput Biol Med_"
publication_types = ["2"]

abstract = "Objective:The development of new technologies has generated vast amount of data that can be analyzed to better understand and predict the glycemic behavior of people living with type 1 diabetes. This paper aims to assess whether a data-driven approach can accurately and safely predict blood glucose levels in patients with type 1 diabetes exercising in free-living conditions. Methods:Multiple machine learning (XGBoost, Random Forest) and deep learning (LSTM, CNN-LSTM, Dual-encoder with Attention layer) regression models were considered. Each deep-learning model was implemented twice: first, as a personalized model trained solely on the target patient’s data, and second, as a fine-tuned model of a population-based training model. The datasets used for training and testing the models were derived from the Type 1 Diabetes Exercise Initiative (T1DEXI). A total of 79 patients in T1DEXI met our inclusion criteria. Our models used various features related to continuous glucose monitoring, insulin pumps, carbohydrate intake, exercise (intensity and duration), and physical activity-related information (steps and heart rate). This data was available for four weeks for each of the 79 included patients. Three prediction horizons (10, 20, and 30 min) were tested and analyzed. Results:For each patient, there always exists either a machine learning or a deep learning model that conveniently predicts BGLs for up to 30 min. The best performing model differs from one patient to another. When considering the best performing model for each patient, the median and the mean Root Mean Squared Error (RMSE) values (across the 79 patients) for predictions made 10 min ahead were 6.99 mg/dL and 7.46 mg/dL, respectively. For predictions made 30 min ahead, the median and mean RMSE values were 16.85 mg/dL and 17.74 mg/dL, respectively. The majority of the predictions output by the best model of each patient fell within the clinically safe zones A and B of the Clarke Error Grid (CEG), with almost no predictions falling into the unsafe zone E. The most challenging patient to predict 30 min ahead achieved an RMSE value of 32.31 mg/dL (with the corresponding best performing model). The best-predicted patient had an RMSE value of 10.48 mg/dL. Predicting blood glucose levels was more difficult during and after exercise, resulting in higher RMSE values on average. Prediction errors during and after physical activity (two hours and four hours after) generally remained within the clinical safe zones of the CEG with less than 0.5% of predictions falling into the harmful zones D and E, regardless of the exercise category. Conclusions:Data-driven approaches can accurately predict blood glucose levels in type 1 diabetes patients exercising in free-living conditions. The best-performing model varies across patients. Approaches in which a population-based model is initially trained and then fine-tuned for each individual patient generally achieve the best performance for the majority of patients. Some patients remain challenging to predict with no straightforward explanation of why a patient is more challenging to predict than another."

abstract_short = ""

image_preview = ""
selected = false
projects = []
tags = []

url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "DOI", url = "https://doi.org/10.1016/j.compbiomed.2025.110015"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
