# Pewlett_Hackard_Analysis
Use SQL Analysis to aggregate database
## Overview of the analysis 
Bobby is an HR Analyst who is tasked with the responsibility to identify how many *'baby boomers'* are retiring in the next few years and how many new positions will be needed to be filled using '**PostgreSQL**'. This analysis will help prepare Bobby’s manager for the *“silver tsunami”* as many current employees reach retirement age.
## Results 
The total number of retiring employees (who were born between *January 1, 1952 and December 31, 1955*) aggregated by their most recent titles can be found using the following code:
![image](https://user-images.githubusercontent.com/84694664/129496982-20831dfe-2f17-490f-9e2a-f678a97a4247.png)

- There are **7** job roles which will have several employees retiring in the next few years. Here is a snapshot of the total number of employees retiring for each job title.

![Retiring Employees by Titles](https://user-images.githubusercontent.com/84694664/129493951-929947f5-82f5-4af0-861f-893e3be82594.PNG)

- **'Senior Engineer'** is the title with most number of employees who will be retiring and need to be backfilled soon by the company.

The company wants to identify employees who are eligible for mentorship employees who were born between *January 1, 1965 and December 31, 1965*. Following code was used to identify them:
![image](https://user-images.githubusercontent.com/84694664/129497113-acc386fc-d6fb-4ac8-a092-fdcd6dad6fad.png)

- **1549** employeees have been identified for mentorship program as most of the employees approach retirement.

![Employees Eligible for Mentorship](https://user-images.githubusercontent.com/84694664/129494141-a8d39d82-163a-4e86-9fe8-9daefb6ab823.PNG)


## Summary: 
**90398** roles are going to open up which will need to be filled in as the employees retire. However, there are only **1549** employees eligible for mentorship. There is a huge gap which will need to be backfilled with additional hiring. 

The employees eligible for mentorship should be grouped by titles and departments to match them to appropriate mentors for e.g. the *Engineers* in the *Research* team should be paired with *Senior Engineers* who are going to retire.

Additional analysis can be done to identify younger employees (born between 1965 to 1970) for mid-level roles such as *'Senior Engineer'* and *'Senior Staff'* and fast track them through training and mentorship.
