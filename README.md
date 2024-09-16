# Project Description:  

A series of 4 exercises, each simulating a need from a company:  
*   practice #1: testing if the average lifetime of bulbs is longer or not. 
*   practice #2: testing if the blood pressure reduction of a medication is less than 15mmHg or not. 
*   practice #3: testing if the average lifespan of batteries is lower than 500 hours, or not. 
*   practice #4: testing if the customer satisfaction rate has decreased, or not, after a return policy change. 

For each practice, I formulated key statistics: **mean, sample size, sample mean and significance level**, expressing every data in **LaTex**.  
I also formulated the **null hypothesis ($H_0$, $H_1$)**. 

When needed, I **calculated the missing statistics**, like **population standard deviation** or the **sample standard deviation**, and therefore also **selecting the relevant test** (in this case, the t test). 

## Practice Exercise #1:  
You are a quality control analyst in a factory that produces light bulbs. The factory claims that the average lifetime of their light bulbs is 1,000 hours.  

However, you suspect that the true average lifetime of the bulbs might be more than this, so you decide to test it.

### Objectives  
1.   Determine if the average lifetime is lesser than or equal to 1000 hours ($H_0$), or not ($H_1$).
     
2.   Present your conclusions and recommendations

### Dataset:  
The dataset was **randomly created using pandas**, and then imported as a csv file.  
It has 36 rows (sample size).  

### Methodology:
This is a right-tailed test.  
The pop. standard deviation is unknown so we need the t score approach. For that I first calculated the sample mean to then calculate the sample standard deviation. Once I calculated my t score and my corresponding critical value, I reached a  
conclusion on null hypothesis. 

## Practice Exercise #2:  
You are a researcher analyzing the effectiveness of a new medication. The company claims that the medication reduces blood pressure by an average of 15 mmHg.  

You want to test if the medication actually reduces blood pressure by less than this amount.

### Objectives  
1.   Determine if the reduction is greater than or equal to 15 mmHg ($H_0$), or not ($H_1$).
     
2.   Present your conclusions and recommendations

### Dataset:  
The dataset was **randomly created using pandas**, and then imported as a csv file.  
It has 30 rows (sample size).   

### Methodology:
Using the z score to extract the p value and compare it to our significance level to conclude on a decision regarding the null hypothesis. 

## Practice Exercise #3:  
You are a data analyst working for a company that manufactures batteries. The company claims that their batteries have an average lifespan of 500 hours.  

You suspect that the actual lifespan is lower, so you decide to test this claim.

### Objectives  
1.   Determine if the lifespan is greater than or equal to 500 hours ($H_0$), or not ($H_1$).
     
2.   Present your conclusions and recommendations

### Dataset:  
The dataset was **randomly created using pandas**, and then imported as a csv file.  
It has 35 rows (sample size).   

### Methodology:
This is a left-tailed test.  
The pop. standard deviation is unknown so we need the t score approach. For that I first calculated the sample mean to then calculate the sample standard deviation. Once I calculated my t score and my corresponding critical value, I reached a  
conclusion on null hypothesis. 

## Practice Exercise #4:  
You work as an analyst for a retail company that is interested in understanding customer satisfaction. The company claims that 80% of its customers are satisfied with their service.  

However, after a recent change in their return policy, you suspect that the satisfaction rate might have decreased. You decide to test this claim.

### Objectives  
1.   Determine if the customer satisfaction rate is greater than or equal to 0.8 ($H_0$), or not ($H_1$).
     
2.   Present your conclusions and recommendations

### Dataset:  
This needs a hypothesis proportion test.  
Sample size = 150.

### Methodology:
Using the z score to extract the p value and compare it to our significance level to conclude on a decision regarding the null hypothesis. 


# Contact me:
*   LinkedIn: https://www.linkedin.com/in/jytran-datascience

My name is Jean-Yves TRAN, I bring 9 years of promotional video creation and project management into Data. My goal is to first become an ML Engineer and leverage that experience to mature into a Data Scientist.
