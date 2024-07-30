# SQL-Based Investigation of Suspicious Logins and Security Updates


## Project description

In this project, I am a security professional at a large organization. Part of my job is to investigate security issues to help keep the system secure. I recently discovered some potential security issues that involve login attempts and employee machines.

My task is to examine the organization’s data in their “employees” and “log_in_attempts” tables. I’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

log_in_attempts table:

![image](https://github.com/user-attachments/assets/72a3e97e-ea69-43ed-92ac-af2ab296ffd5)



employees table:

![image](https://github.com/user-attachments/assets/6cd942ee-1f82-43b9-af53-1d8d31196089)



## Retrieve after hours failed login attempts

I recently discovered a potential security incident that occurred after business hours. To investigate this, I need to query the “log_in_attempts” table and review after hours login activity. I will use filters in SQL to create a query that identifies all failed login attempts that occurred after 18:00.

![image](https://github.com/user-attachments/assets/c1f872cc-b02a-4acd-bf96-87c62c68a19c)



## Retrieve login attempts on specific dates

A suspicious event occurred on 2022-05-09. To investigate this event, I’m going to review all login attempts that occurred on this day and the day before. I’ll use filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 and 2022-05-08.

![image](https://github.com/user-attachments/assets/f2296f59-11ab-43aa-a00f-1a3339dfbeec)



## Retrieve login attempts outside of Mexico

There’s been suspicious activity with login attempts, but my team has determined that this activity didn't originate in Mexico. Now, I need to investigate login attempts that occurred outside of Mexico. I’ll use filters in SQL to create a query that identifies all login attempts that occurred outside of Mexico. (When referring to Mexico, the country column contains values of both MEX and MEXICO, and I will need to use the LIKE keyword with % to make sure my query reflects this.)

![image](https://github.com/user-attachments/assets/3f3f3e5d-c834-4b4b-9dab-d1f66deed79b)



## Retrieve employees in Marketing

My team wants to perform security updates on specific employee machines in the Marketing department. I’m responsible for getting information on these employee machines and will need to query the “employees” table. I’ll use filters in SQL to create a query that identifies all employees in the Marketing department for all offices in the East building. I’ll use the LIKE keyword with % to filter for the East building.

![image](https://github.com/user-attachments/assets/53519b2d-a214-4b40-bf34-49e004b987b9)



## Retrieve employees in Finance or Sales

My team now needs to perform a different security update on machines for employees in the Sales and Finance departments. I’ll use filters in SQL to create a query that identifies all employees in the Sales and Finance departments. 

![image](https://github.com/user-attachments/assets/fd36b07b-5d40-4cec-a6ab-484351c10263)



## Retrieve all employees not in IT

My team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. I’ll use filters in SQL to create a query that identifies all employees not in the IT department. 

![image](https://github.com/user-attachments/assets/757dbab7-6c90-49e8-a059-5feaf0d77090)



## Summary

As a security professional, I was responsible for investigating potential security issues related to login attempts and employee machines in our organization's database. Using SQL queries, I analyzed data from the "employees" and "log_in_attempts" tables. I first focused on an after-hours incident by filtering failed login attempts after 18:00. For another suspicious event on 2022-05-09, I examined all login attempts on that day and the previous day. Our team identified that the suspicious activity didn't originate in Mexico, so I crafted a query to find all login attempts outside of Mexico. I also gathered information about employee machines in the Marketing department in the East building using the LIKE keyword. Further updates targeted machines in the Sales and Finance departments, and I identified these employees with specific SQL queries. Lastly, I excluded IT department employees who had already received updates by applying appropriate SQL filters.
