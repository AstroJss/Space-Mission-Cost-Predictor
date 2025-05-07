# 🚀AI Space Mission Cost Predictor

## 🌌Inspiration

Whether it's the SpaceX chopsticks catching the Starship rocket booster or Katy Perry going to space, the humanity is slowly advancing into an era where outer space exploration missions are becoming more frequent and accessible and will only be going to increase in the coming decades. Although it is slow but  consistent, companies like SpaceX and Blue Origin are trying to make Space Travel more affordable with time. 

## 📝Description

With this inspiration in mind, the AI model predicts the cost for future missions based on the recent Space Missions data. The model has been trained upon Decision Trees and Random Forest Regression algorithms using Py libraries including `pandas`, `seaborn`, `sklearn` and `matplotlib`. For optimization and regularization, gradient boosting techniques such as XGBoost were applied to achieve an accuracy of around **~90%** on the testing data. 

🎯 One of the main challenges faced during the training was the feature dominance and overfitting. Since the dominant feature was an importnat factor which could not be neglected, its influence was reduced using Ridge Regression methods and, hence, optimize the results.

## ✨Features:

- Predicts costs and budgets for Outer Space Missions
- Clearly displays feature correlation plots
- Shows top contributing features
- Handles overfitting

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
