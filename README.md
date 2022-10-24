# Gun Trends in the United States.
Investigated gun registration trends in the U.S. between (1999-2016).
## Introduction

Gun ownership and the use of firearms has become an ongoing debate in the United States. In the last few years, mass shootings have persuaded people to push for stricter gun laws throughout the country. Between (1999-2016) have background checks for gun registrations decreased or increased? What do the gun trends look like in each state and which ones have the most and least gun registration growth? Finally, are there any factors associated with higher gun registrations per capita based on census data? 

This data will investigate gun registrations using the [U.S. Census Data](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a554c_u.s.-census-data/u.s.-census-data.csv&sa=D&source=editors&ust=1664580025057728&usg=AOvVaw1slpDgPRWt5B4GRqctBk0-) and the [FBI's Gun Data](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a4db8_gun-data/gun-data.xlsx&sa=D&source=editors&ust=1664580025057165&usg=AOvVaw1wWw7yeP4NA3cv1gmxe_k8). The FBI's gun data comes from the National Instant Criminal Background Check System (NICS). Original source can be found on [Github](https://www.google.com/url?q=https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md&sa=D&source=editors&ust=1664580025055946&usg=AOvVaw3kp7EnqBt_l3Xs7U0FvQ1Z).

There are a few limitations to this data. One of the most important limitations to take into consideration is that the data from the NCIS is in regards to the number of background checks initiated and not firearms sold. Some examples of this include, a background check being conducted for a concealed carry permit or a state conducting multiple background checks, over a span of time on a single person, to ensure continued eligibility to conceal carry. The state of Kentucky is known for conducting background checks on a single person, every year, to ensure eligibility to conceal carry. Therefore, no correlation can be made between background checks conducted and firearms sold.

## Conclusions
In conclusion, I investigated three questions regarding gun trends in the U.S. between the years (1999-2016). These three questions consisted of:

   *1.) Between the years (1999-2016), have background checks for gun registrations increased or decreased?*

   *2.) Which states have the most and least gun registration growth?*

   *3.) Are there any factors associated with higher gun registrations per capita based on census data?*

### Between the years (1999-2016), have background checks for gun registrations increased or decreased.

Overall, there has been a significant increase in gun registration growth in the U.S. between (1999-2016). In 1999, there was a total of 9,038,315 background checks completed for gun registrations compared to 2016 with a total of 27,405,549 background checks completed.

This increase is shown in the dataframe and line graph below:
![image](https://user-images.githubusercontent.com/100544166/197529498-f570b34c-8fd6-4edd-8adb-b61a9011ca41.png)


![image](https://user-images.githubusercontent.com/100544166/197528590-f9ffb44d-3efc-4d9f-a59e-c86be27355f4.png)

### Which states have the most and least gun registration growth?

First, I found the states with the least and most amount of total background checks completed. Hawaii has consistently had the least amount of total gun registrations per year. The state with the most gun registrations has varied by year, however, Kentucky has had the most total gun registrations between 1999-2016 overall.

**It should be noted, one of the limitations was that Kentucky is a state known for conducting background checks on a single person, every year, to ensure eligibility to conceal carry. This could be a reason why they have some of the highest background checks completed for gun registrations per year.**

Next, I found the difference in total # of background checks completed for each state in the years 1999 and 2016. I sorted the dataframe by the ['difference'] column for each state. This dataframe shows that Hawaii had the lowest difference at a total of 11,338 while Kentucky had the highest at 3,428,635.

Finally, I got the percent increase for each state between the years 1999 and 2016 and sorted the dataframe by the ['percentage'] column. This dataframe shows that Arkansas had the least gun registration growth at about 31% and Kentucky had the most at about 93%.

![image](https://user-images.githubusercontent.com/100544166/197529927-55e2752a-8588-4b35-be68-5851e000150d.png)

![image](https://user-images.githubusercontent.com/100544166/197530207-a327cdbe-2f33-449e-ad26-aa7ce27876d4.png)

![image](https://user-images.githubusercontent.com/100544166/197530414-258204da-24af-413c-9828-e7aa17ad60a7.png)
![image](https://user-images.githubusercontent.com/100544166/197530635-914656bd-cf62-4142-bc63-1a751a510f00.png)
![image](https://user-images.githubusercontent.com/100544166/197530724-2ca5f7db-d981-4a6a-82bd-68a86fc7f13f.png)

![image](https://user-images.githubusercontent.com/100544166/197530975-42143b60-3b22-46b5-889f-f829a350e9ef.png)
![image](https://user-images.githubusercontent.com/100544166/197531124-7d458f0c-6b45-483b-b382-8e4c94715093.png)
![image](https://user-images.githubusercontent.com/100544166/197531233-24c91d4d-aae8-45b0-906e-893546f7c988.png)

### Are there any factors associated with higher gun registrations per capita based on census data?

I joined the FBI and Census datframes together in an effort to find any correlations between gun registration growth and population growth or race demographics per state.
 
The joined dataframe appeared to show there is no correlation between gun registration growth and population growth or any race demographics.
 
The 4 scatter plots below compare 'Gun Registration Growth' to 'Population Growth', 'White only (not Hispanic or Latino)', Hispanic or Latino', and 'Black or African American'. The scatter plots affirmed that there is no correlation between gun registration growth and either population or race demographics.

![image](https://user-images.githubusercontent.com/100544166/197531585-7125d14f-1038-4acc-b773-320aaeed43af.png)

![image](https://user-images.githubusercontent.com/100544166/197531630-f29527cd-d04f-4c47-9847-596ccb30b3e3.png)

![image](https://user-images.githubusercontent.com/100544166/197531662-2208ff41-6f70-4e3e-8efc-633d4054cace.png)

![image](https://user-images.githubusercontent.com/100544166/197531700-cd36966a-0b1a-4187-827f-55ebea50260a.png)


