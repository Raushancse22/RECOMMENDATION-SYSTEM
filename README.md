# RECOMMENDATION-SYSTEM

# COMPANY : CODTECH IT SOLUTIONS

# NAME : RAUSHAN KUMAR

# INTERN ID* : CT04DN754

# DOMAIN : MACHINE LEARNING

# DURATION : 4 WEEK

# MENTOR : NEELA SANTOSH

# TASK DESCRIPTION 
In this project, a simple recommendation system was implemented using Matrix Factorization, a technique commonly used in collaborative filtering. The goal was to predict unknown user-item ratings based on known interactions, enabling personalized content delivery.

The task followed these key steps:

Data Creation:

A synthetic movie ratings dataset was created consisting of user IDs, movie IDs, and corresponding ratings.

Matrix Construction:

The user-item interaction matrix was constructed, where each cell represents a user's rating for a specific movie.

Missing entries were initialized with zero to simulate unknown preferences.

Model Development:

A custom Matrix Factorization model using Stochastic Gradient Descent (SGD) was built from scratch.

The user and item latent factor matrices were initialized and iteratively updated to minimize the root mean square error (RMSE) between the predicted and actual ratings.

Training & Optimization:

The model was trained over multiple iterations to refine predictions.

A loss function was used to guide the optimization, balancing prediction accuracy and regularization.

Prediction & Evaluation:

The final predicted ratings matrix was generated.

Heatmaps were plotted to visually compare the original vs. predicted ratings, helping evaluate the model’s performance.

# output 
![Image](https://github.com/user-attachments/assets/66629577-def5-4615-89fd-90027bf967c3)
![Image](https://github.com/user-attachments/assets/6fd4c631-d4e1-4988-b4c0-9076839a4f09)
