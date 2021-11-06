# Prison Admission Data Project
### About: 

For this project, I implemented data analysis using R. I used the libraries tidyr, dplyr, plotly and ggplot2 which helped me to build the project. I analyzed data of various prison data to gain a better understanding and insight of general trends of prison immates and convictions. 
 
### Results: 

First, I loaded the datasets onto data frames.

![Screen Shot 2021-11-05 at 8 12 31 PM](https://user-images.githubusercontent.com/89553126/140592904-959494e8-636e-4a70-86f0-f19d1179d1d7.png)

I inspected the datasets with the functions *head* to gain insight in what I wanted to gleam from the data and extract from it.


Afterwards, I viewed the data to see what I am working with. 

![Screen Shot 2021-11-06 at 2 57 35 PM](https://user-images.githubusercontent.com/89553126/140622269-1a78a511-7736-431c-a004-2855edaba60a.png)

***division_allocation* Data Frame**

![Screen Shot 2021-11-06 at 3 02 18 PM](https://user-images.githubusercontent.com/89553126/140622364-4460dc5a-1130-4613-8102-7580d921c325.png)

***fiscal_year* Data Frame**

![Screen Shot 2021-11-06 at 3 16 12 PM](https://user-images.githubusercontent.com/89553126/140622722-10d801f0-c1d5-4607-970e-d05e0984b998.png)

***residential_population* Data Frame**

![Screen Shot 2021-11-06 at 3 16 37 PM](https://user-images.githubusercontent.com/89553126/140622727-258eb3f3-22f1-4137-baf0-88ca65afb8ce.png)

***returns* Data Frame**

![Screen Shot 2021-11-06 at 3 17 00 PM](https://user-images.githubusercontent.com/89553126/140622741-8c95a05c-6933-45e7-b4cb-36fb1f48493b.png)

Afterwards, I wanted to know the average number of offenders in a residential facility.
 
![Screen Shot 2021-11-06 at 3 21 32 PM](https://user-images.githubusercontent.com/89553126/140622821-2787ff02-9828-4ab4-8533-6367438a0e1a.png)

The average number of offenders was 458.25 persons in facilities. 

I also looked into the standard deviation of the number of offenders in the residential facilities.  

![Screen Shot 2021-11-06 at 3 23 34 PM](https://user-images.githubusercontent.com/89553126/140622868-2a7b0a12-5e1a-4a26-aed3-24383e9bab77.png)

The standard deviation was 173.5538.

Next, I was interested in the number of days bewteen getting realease from custody and being incarcerated again in number of months units.
 
![Screen Shot 2021-11-06 at 3 28 06 PM](https://user-images.githubusercontent.com/89553126/140622933-72cf37db-35b0-452f-9232-4c9c75f202fa.png)

![Screen Shot 2021-11-06 at 3 29 07 PM](https://user-images.githubusercontent.com/89553126/140622956-0d25fc14-9f7b-4b4d-aa41-03d3566c5f13.png)

Afterwards, I wanted to know how much division overhead was provided for each program.
 
![Screen Shot 2021-11-06 at 3 33 53 PM](https://user-images.githubusercontent.com/89553126/140623047-0299693d-483b-4b6b-9909-bdceddca0bae.png)

The overhead for A, B, C and D were 2.857143, 4, 1.333333, and 2.222222 respectfully. This is teh overhead rate, meaning it costs the program this many dollars in overhead costs for every dollar in direct labor expenses.

Afterwards,  I calculated the percentage change in the number of offenders admitted ot prison from fiscal year 2005 to fiscal year 2010.
 
![Screen Shot 2021-11-06 at 3 37 33 PM](https://user-images.githubusercontent.com/89553126/140623131-b7368ebe-8bd3-48ac-a14b-ec6e2bc273b9.png)

![Screen Shot 2021-11-06 at 3 38 24 PM](https://user-images.githubusercontent.com/89553126/140623149-6f61bce3-1d4d-4ca0-8e83-a31270a35758.png)

The produced data demonstrates that there has been a percentage increase in direct court commitments, a decrease percentage change in parole revocations and a insignificant change in probation revocations.

Next, the average number of offenders admitted to prison from fiscal year 2005 to fiscal year 2010.

![Screen Shot 2021-11-06 at 3 43 06 PM](https://user-images.githubusercontent.com/89553126/140623250-b90458e2-5999-4b86-9e67-091e06a011cd.png)

Which was outputted as a message, 

![Screen Shot 2021-11-06 at 3 43 26 PM](https://user-images.githubusercontent.com/89553126/140623260-ec2d0210-a735-4410-b905-f9d70c5a5501.png).

Afterwards, I then got the percentage of the total number of offenders admitted to presion from each of the admission categoary for each fiscal year.  

![Screen Shot 2021-11-06 at 3 45 26 PM](https://user-images.githubusercontent.com/89553126/140623303-1d92a489-1158-4dff-8975-9b5e3b788e1b.png)

Finally, I can analyze the data trends in plots with ggplot2 and best fit plots with plotly.

![Screen Shot 2021-11-06 at 3 48 31 PM](https://user-images.githubusercontent.com/89553126/140623372-97eb8dfa-cf4c-4b41-8768-38bd7c6aa058.png)

![Screen Shot 2021-11-06 at 3 49 04 PM](https://user-images.githubusercontent.com/89553126/140623373-8e118947-21ef-4473-814c-35469cf17735.png)

![Screen Shot 2021-11-06 at 3 49 30 PM](https://user-images.githubusercontent.com/89553126/140623384-c49ea6ca-f3ea-4487-8af9-9aee5fa263ee.png)

![Screen Shot 2021-11-06 at 3 49 43 PM](https://user-images.githubusercontent.com/89553126/140623386-04dd6587-ff4a-4736-906f-7365a5d4e44d.png)

![Screen Shot 2021-11-06 at 3 50 05 PM](https://user-images.githubusercontent.com/89553126/140623407-9e427e45-f616-4270-94a3-f6558982ed0d.png)

![Screen Shot 2021-11-06 at 3 50 19 PM](https://user-images.githubusercontent.com/89553126/140623413-19d2648d-bb0b-4d60-94ca-6148a38d1747.png)

![Screen Shot 2021-11-06 at 3 50 44 PM](https://user-images.githubusercontent.com/89553126/140623437-a0c2c0d8-53c0-44f7-b208-a92d0757d806.png)

![Screen Shot 2021-11-06 at 3 50 59 PM](https://user-images.githubusercontent.com/89553126/140623441-a9e1cc00-a106-4c9d-acc1-d6e0c1f61070.png)
