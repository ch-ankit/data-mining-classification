# Data Mining Classification Task with Hotel Booking Dataset

This repository contains code for a data mining classification task that uses the Hotel Booking Demand dataset, available on Kaggle [here](https://www.kaggle.com/jessemostipak/hotel-booking-demand). The goal of this task is to compare different classification algorithms and evaluate their performance based on the ROC curve.

## Dataset

The Hotel Booking Demand dataset contains information about hotel bookings from two hotels located in Portugal: a city hotel and a resort hotel. The dataset includes information about bookings such as the lead time, arrival date, duration of stay, number of adults/children, and more.

## Classification Algorithms

The following classification algorithms were used in this task:

- Decision Tree
- K-Nearest Neighbors (KNN)
- SVM
- Naive Bayes
- Neural Network

## Evaluation Metric

The performance of the classification algorithms was evaluated based on the ROC curve. The ROC curve is a graphical representation of the performance of a binary classifier as its discrimination threshold is varied. It shows the trade-off between the true positive rate (TPR) and false positive rate (FPR) at different classification thresholds.

## Files

- `hotel_bookings.csv`: the original dataset downloaded from Kaggle
- `comparision_output1.ows` : contains visualization of the given data
- `EDA.ows` : an orange file which shows exploratory analysis and transformation of data
- `DM.ipynb`: a Jupyter notebook containing the code for the data pre processing tasks
- `algo_comparisions.ows` : orange file showing visual modelling of the comparision of the data fed into classification algorithms mentioned above
- `README.md`: this file

## Usage

To run the code in the `DM.ipynb` notebook, you will need to have Python 3 and Jupyter Notebook installed on your machine. 
Then, start Jupyter Notebook and open the `DM.ipynb` file to run the code. It will provide a pre processed dataset which is then to be fed to Orange.


## Results

The results of the classification task are summarized in the `DM.ipynb` notebook. The ROC curves for each of the classification algorithms are shown, along with the area under the curve (AUC) metric. Based on the AUC metric, the Naive Bayes algorithm and the Neural Network algorithm performed the best among the four algorithms that were tested.

## Conclusion

This project demonstrated how to use different classification algorithms to predict hotel booking cancellations. The ROC curve was used to evaluate the performance of the algorithms, and the results showed that the Naive Bayes algorithm and the Neural Network algorithm had the best performance. This project could be extended by trying out other classification algorithms or by tuning the hyperparameters of the existing algorithms to see if better performance can be achieved.
