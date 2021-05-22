# HPC-Libraries-comparision

We compared Pymp and Joblib on 2 majorly used datasets in the machine learning world. Those are Image and Stocks.

Below are the links for the datasets we used from Kaggle:<br />
https://www.kaggle.com/jacksoncrow/stock-market-dataset <br />
https://www.kaggle.com/c/dogs-vs-cats/data <br />

Amount of Dataset used:<br />
200 stocks files<br />
2000 images of cats and dogs

We used a little bit of hyberparameter tuning to check the performance of both libraries on KNN algorithm.<br />
We choosed KNN because it is an non-paramteric machine learning algorithm and has the dataset grows the time complexity of the algorithm increases exponentially.

The results we acheived by comparing the libraries:<br />
![alt text](https://github.com/FanindhraThirunagaru/HPC-Libraries-comparision/blob/cc3a153c04c7d3717c3997e44531d26d31d1e232/Images/image%20libraries%20comparision.jpeg)
![alt text](https://github.com/FanindhraThirunagaru/HPC-Libraries-comparision/blob/cc3a153c04c7d3717c3997e44531d26d31d1e232/Images/image%20processors%20comparision.jpeg)
![alt text](https://github.com/FanindhraThirunagaru/HPC-Libraries-comparision/blob/cc3a153c04c7d3717c3997e44531d26d31d1e232/Images/stocks%20results.jpeg)


Note: The device used for testing is Quad-core Linux Environment. The performance of the libraries will be depending on the device configuaration.
