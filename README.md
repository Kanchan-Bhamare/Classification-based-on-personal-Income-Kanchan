# CLASSIFICATION BASED ON PERSONAL INCOME

![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/11-Factors-Affecting-Job-Satisfaction-Besides-the-Obvious.png?raw=true)
 
 
 Introduction to classification case Study :

## - Problem Statement :

 - "Subsidy Inc." delivers subsidies to individuals based on their income. 
 - Accurate income data is one of the hardest pieces of data to obtain across the world.
 - Subsidy Inc. has obtained a large data set of authenticated data on individual income, demographic parameters, and few financial parameters. 
 - Subsidy Inc. wishes us to: Develop an income classifier system for individuals.

## The Objective is to :

Simplify the data system by reducing the number of variables to be studied, without sacrificing too much accuracy. Such a system would help subsidy Inc. in planning system subsidy outlay, monitoring and preventing misuse.
![enter image description here](https://image.shutterstock.com/image-photo/close-customer-hand-choose-smiley-600w-1907692888.jpg)

To checkout my notebook please click [here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/EDA%20PROJECT-CLASSIFICATION.ipynb)

## Description of dataset :

to checkout my dataset please click ![here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/income%281%29.csv)


## Exploratory Data Analysis :


 1. **Gender Vs Salary :**
 
|   SalStat gender   |  greater than 50,000         |  less than 50,000

|   Female           |         0.113678             |       0.886322

|   Male             |          0.313837            |       0.686163





 2. **Frequency distribution of 'Salary Status' :**
 
 
 
![enter image description here](https://raw.githubusercontent.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/e5c2b711774b151b9022b523afd9664efdb48e01/Picture1.png)



 3. **Histogram of Age :**


![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture2.png?raw=true)



 4. **Box-plot Age vs. Salary Status :**


![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture3.png?raw=true)



 5. **Job Type vs. Salary Status**


 ![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture4-job-salStat.png?raw=true)


![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture5-job-salstat.png?raw=true)

 

 - From the above table it is visible that 56% of self employed people
   earn more than 50,000 USD per year.
 - Hence an important variable in avoiding the misuse of subsidies. 


 6 . **Education vs. Salary Status :**
 


![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture6-Edu-SalStat.png?raw=true)
 
 
 from the above graph we can see that people who have done Doctorate, Masters, Prof-school are more likely to earn above 50,000 USD per year when compared with others. Hence an influencing variable in avoiding the misuse of subsidies.
 


 7 . **Occupation vs. Salary Status**


![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture7-occu-salstat.png?raw=true)


From above observations those who make more than 50,000 USD per year are more likely to work as managers and professionals, hence an important variable in avoiding the misuse of subsidies.





 8 . **Histogram of Capital gain :**
 
 
 
 ![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture8-hist-capital-gain.png?raw=true)
 - 92%(27611) of the capital gain is 0.





 9 . **Histogram of Capital Loss :**



![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture9-Hist-capital-loss.png?raw=true)

 - 95%(28721) of the capital loss is 0.





 10 . **Box-Plot- Hours Per Week vs. Salary Status :**
 
 ![enter image description here](https://github.com/Kanchan-Bhamare/Classification-based-on-personal-Income-Kanchan/blob/main/Picture10-hpw.png?raw=true)
 
 - From the above plot it is clearly visible that those who make more than 50,000 USD per year are more likely to spend 40-50 hours per week.
 - This variable can contribute in classifying the individual's salary status since there is association between salary status and hours per week.
 
