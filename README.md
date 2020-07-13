# JanataHack-Demad-Forecasting
Predictive Modeling for JanataHack: Demand Forecasting competition on Analytics Vidhya
# competition link: https://datahack.analyticsvidhya.com/contest/janatahack-demand-forecasting/

I have used two jupyter notebooks:
1.) Decision Tree, Random Forest and XGBoost using sklearn
2.) Deep Learning with Keras

* Data Preprocessing envolves three steps: 
i) Resampling dataset, dropping Null values containing rows (there's only one row so we can drop it without hesitating)
ii) Feature Engineering step where we create two feature - day of week and is base price equal to total price (we can also take difference which I took in deep learning model).
iii) dropping unnecessaary features like date and recordID
iv) Extra step for XGBoost and Deep Learning Model since they can't handle categorical features like sku_id and store_id, so we one hot encode these values.

* Decision Tree and XGBoost are already tuned according to public dataset used in active competition, but XGBoost takes a lot of time to produce results so I couldn't tune it for better results, but code is fully functionable, if any issue is there kindly open it in Issues thread.

* Deep Learning model is also tuned based on public dataset and fully functional, I got best results using deep learning.
