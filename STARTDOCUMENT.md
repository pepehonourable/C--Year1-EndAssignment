# Startdocument for Assignment 9 (Catering)

Startdocument of Nathan Mills. Student number 4996046.

## Problem description

A company provides catering services. The administration for a number of
customers is processed for a period indicated by a start and end date.
A customer can take a starter (3 euros) and/or a main course (5 euros) and/or a
dessert (2 euros) each day.
A program must be developed in which the customer's name and the number
of starters, number of main courses and number of desserts he/she had are
registered. The company ultimately wants to be presented with the following
information:
> The total amount of turnover;
> The average daily turnover;
> The name of the customer who has made purchases for the highest
amount;
> The name of the customers who have had starters but have never had
a dessert;
> The names of the customers who have made purchases for a higher
amount than the average per customer. 

### Input & Output

Below are all the user input and outputs

### Input

|Case|Type|Conditions|
|----|----|----------|
|Customer name|`String`|Not empty|
|Start date|`DateTime`|Not empty|
|End date|`DateTime`|Not empty|
|Has starter|`Boolean`|Not empty|
|Has main|`Boolean`|Not empty|
|Has dessert|`Boolean`|Not empty|
|Company name|`String`|Not empty|

### Output

|Case|Type|
|----|----|
|Course daily cost|`Int`|
|Course total cost|`Int`|
|Total turnover|`Int`|
|Average daily turnover|`Int`|
|Big spenders|`List`|
|Highest spender|`String`|
|Starter no dessert|`List`|

# Class diagram

![image](https://user-images.githubusercontent.com/91469944/172644612-c93c4235-7199-4407-afec-74ddc40d328b.png)

# TestData

### Customer

|ID|Input|Code|
|--|-----|----|
|1|Name: John|addCustomer("John")|
|2|Name: Adam|addCustomer("Adam")|

### Course

|ID|Input|Code|
|--|-----|----|
|1|Name: John Startdate: 01/06/2022 Enddate: 05/06/2022 hasStarter: Yes hasMain: Yes hasDessert: No|addCourse("John", "01/06/2022", "05/06/2022", Yes, Yes, No)|
|2|Name: Adam Startdate: 03/06/2022 Enddate: 06/06/2022 hasStarter: No hasMain: Yes hasDessert: Yes|addCourse("John", "03/06/2022", "06/06/2022", No, Yes, Yes)|

### Company

|ID|Input|Code|
|--|-----|----|
|1|Company: Ramzi's Kitchen|addCompany("Ramzis Kitchen")|
|2|Company: Nathan's Finger Bites|addCompany("Nathans Finger bites")|

### Test Cases

![image](https://user-images.githubusercontent.com/91469944/173319290-2bd70462-bfd0-4ba1-bd73-df22cff5e33a.png)

