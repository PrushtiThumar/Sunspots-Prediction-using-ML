This project aims to analyze and predict solar cycles using historical sunspot data spanning from 1749 to 2021. Leveraging time series analysis and deep learning techniques, an LSTM-based model was developed to forecast sunspot counts. The project highlights advanced preprocessing, data visualization, model optimization, and validation to achieve precise predictions.


Features
Time Series Analysis: Explored trends and cycles in historical sunspot data.
Visualization: Generated insightful plots to observe solar cycle patterns and data distribution.
Deep Learning Model: Built and trained an LSTM-based model augmented with Conv1D layers for robust forecasting.
Optimization: Used learning rate scheduling to determine the optimal learning rate.
Evaluation: Assessed model performance using MAE and visualized predicted vs actual data.




Technologies Used
Programming Languages: Python
Libraries: TensorFlow, Pandas, NumPy, Matplotlib, Seaborn


Project Workflow
1. Data Exploration and Preprocessing:
   * Loaded sunspot data and examined its structure.
   * Visualized long-term trends and solar cycles using Matplotlib.
   * Identified patterns in the data distribution and outliers with histograms and boxplots.


2. Time Series Data Preparation:
   * Split the data into training and validation sets (90:10 ratio).
   * Created a windowed dataset generator function for input-output sequence preparation.


3. Model Development:
   * Built a Sequential model with Conv1D and LSTM layers for improved feature extraction and temporal learning.
   * Fine-tuned the architecture with Dense layers and Lambda layers to scale outputs.


4. Hyperparameter Optimization:
   * Implemented a learning rate scheduler to identify the optimal learning rate.
   * Visualized the loss vs learning rate to pinpoint the best configuration.


5. Model Training and Validation:
   * Trained the model on the training set with the optimized learning rate.
   * Predicted on validation data and visualized the results.
   * Calculated validation MAE to assess the model's accuracy.


Results
* Visualization: Displayed solar cycle trends and forecasted results compared to actual values.
* Performance: Achieved a Mean Absolute Error (MAE) of 12.59 on the validation dataset.
Future Scope
* Extend the model to forecast upcoming solar cycles.
* Incorporate additional data sources like solar wind speed and geomagnetic indices to enhance prediction accuracy.
* Develop a real-time monitoring system for solar activity prediction.