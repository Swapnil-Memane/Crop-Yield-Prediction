# Crop-Yield-Prediction

🧩 Problem Statement — Crop Yield Prediction

Agricultural productivity is highly influenced by multiple environmental and management factors such as rainfall, temperature, fertilizer usage, and soil nutrient composition (N, P, K).
Farmers and agricultural planners often rely on experience or limited field trials to estimate yield, which can lead to sub-optimal decisions regarding resource allocation and crop planning.

The objective of this project is to develop a predictive model that estimates crop yield (in Quintals per acre) based on measurable agronomic parameters.

Using the given dataset containing features like rainfall, temperature, fertilizer, and soil nutrients, the model aims to:

Identify key factors influencing yield.

Accurately predict expected yield for a given set of input conditions.

Enable data-driven agricultural decision making — optimizing fertilizer usage, irrigation planning, and crop selection.

🎯 Goal

To build and evaluate machine learning models (Linear Regression, Random Forest, Gradient Boosting) using a structured ML pipeline and select the best-performing model via hyperparameter tuning (GridSearchCV).

🧠 Key Questions

Which features most strongly affect crop yield?

How accurately can we predict yield given the environmental and nutrient data?

Can the trained model be generalized to unseen conditions?

📊 Expected Outcome

A tuned ML model capable of predicting yield with high R² and low RMSE.

Insights into which parameters (e.g., rainfall, fertilizer, NPK levels) have the greatest impact on productivity.

A deployable model (best_crop_yield_model.pkl) that can support agronomic decision systems.
