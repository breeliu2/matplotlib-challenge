# pymaceuticals-challenge
## Instructions
This project utilized what we've learned in Matplotlib to generate all the tables and figures needed for Pymaceuticals Inc, a company specializing in anti-cancer medication. We were given data results from their most recent study in which they identified 249 mice with SCC tumor growth and gave them treatment through a variety of drug regimens. Pymaceuticals drug of interest, Capomulin, was compared to other treatment regimens. Over the course of 45 days, tumor development was observed and measured. 

## Tasks
* Import and display the number of unique mice IDs. Check the data for any IDs with duplicate time points and remove any data associated with that mouse ID. Clean the data and display the updated number of unique mice IDs in a new DataFrame. 
Generate a summary statistics table that includes the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. 
<img width="484" alt="Screenshot 2023-04-06 at 10 44 37 PM" src="https://user-images.githubusercontent.com/124847109/230536750-0d517f11-0812-4b38-9655-494211246738.png">

* Generate two identical bar charts, using both Pandas and Matplotlib, that show the number of total data points for each treatment regimen throughout the course of the study. 
- Pandas
![image](https://user-images.githubusercontent.com/124847109/230537105-4670f65e-bb06-4d40-b3db-24cd13da02a7.png)
- Matplotlib
![image](https://user-images.githubusercontent.com/124847109/230537117-9f9d28bb-2b50-486a-812c-01dc40c85b04.png)

* Generate two identical pie charts that show the distribution of female or male mice in the study.
![image](https://user-images.githubusercontent.com/124847109/230537293-927cebc4-dc85-4de9-940b-8eb17dd5a8c3.png)
![image](https://user-images.githubusercontent.com/124847109/230537304-883227c3-ce25-4600-a13b-4fabde0bbb34.png)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then calculate the quartiles and IQR and quantatively determine if there are any potential outliers across the four treatment regimens. 
* Using Matplotlib, generate a box plot of the final tumor volume for all the treatment regimens while highlighting any potenital outliers. 
![image](https://user-images.githubusercontent.com/124847109/230537614-0301ac4b-c1d8-4118-9819-3ce5d317ba44.png)


* Select one mouse that was treated with Capomulin and generate a line plot of tumor volume versus time point for that mouse. 
![image](https://user-images.githubusercontent.com/124847109/230537772-3f7de092-510e-4a9d-b9e6-b95b0d372e6c.png)

* Generate a scatter plot of average tumor volume versus mouse weight for the Capomulin regimen. 
![image](https://user-images.githubusercontent.com/124847109/230537873-95bab548-1b9f-4833-b68f-20556dcc590c.png)

* Calculate the correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen. Then plot the linear regression model on top of the previous scatter plot. 
![image](https://user-images.githubusercontent.com/124847109/230538003-9e88703a-b7f7-4bd9-9450-5c66427bf709.png)





