# ARIMA-MODEL
This python script is a result of a project , made by EL ouataoui Othmane and Bahtat Zakaria , under the guidance of the professor our hassani Ibtissam. 
The Project is about Forecasting a SCOR KPI (Reliability) supply chain model , using python. 
To use this model :
1-you need to change the path of the data base that you wanna process in the script based on your files local pathn, this applies to the output files too.
2-you need to make sure that the data you are using is Stationary since ARIMA model is for stationary data, using the (Fuller test, acf, pacf,...)
3-the data Training / Testing is 80/20
4-The inputs are taken from  KPI sheets and the output are excel files , make sure that the class of the sheets scripts is the same as ur database 
5-You can visualise your Forecasting and change the Arima model factors (m,n,p) by comparing the the data frame test (forecasting output) and the actual data.
