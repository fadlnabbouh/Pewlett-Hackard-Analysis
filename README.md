# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis was to retrieve a list of employees retiring this year by title from Pewlett Hackard, as well as retrieve a list of employees that are eligible for a mentorship program. This mentorship program will allow the company to place individuals close to retirement in mentorship roles where they can mentor newly hired employees.
  

## Results 

The queries used to retrieve the list of employees can be found here: [Employee Database Query](https://github.com/fadlnabbouh/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_challenge.sql).
Four tables were generated by the query: 
- Deliverable 1: [retirement_titles.csv](https://github.com/fadlnabbouh/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv), [unique_titles.csv](https://github.com/fadlnabbouh/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv), and [retiring_titles.csv](https://github.com/fadlnabbouh/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) were used to determine employees retiring from Pewlett Hackard and their respective titles
- Deliverable 2: [mentorship_eligibility.csv](https://github.com/fadlnabbouh/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv) was used to determine eligible employees close to retirement and who may fill mentorship roless for incoming emplyoees. 

Four key takeaways from these deliverables are: 
- The highest number of retiring individuals are Senior Engineers, while the lowest are managers. The company will not require many resources when hiring for manager positions, but will need to higher a significant number of Senior Engineers to fill these roles. 
- The majority of individuals are retiring from Engineer (Senior Engineer, Engineer, and Assistant Engineer) or Staff (Senior Staff and Staff) positions. The company will require more resources to fill these roles than any other role. In addition, when considering the mentorship program, they may want to allocate more mentors to these roles. 
- From the mentorship table, I find that 1,549 people are close to retirement and may be able to fill part time roles as mentors. 
- There are significantly more people retiring than people that will end up being hired to fill those roles, and eligible mentors. This means that the company will need to create a program that can efficiently match multiple employees to one mentor, as a one to one system will not work.

## Summary

As the 'silver tsunami' begins to impact companies, significant increases in resources to hiring practices will be required. With Pewlett-Hackard, the company will see 90,398 employees retire over 4 years. This is significantly higher, approximately 60x higher, than the number of eligible mentors of 1,549. Becuase of this discrepancy, there are not enough qualified mentors to train the next generation of employees. The company will require a program that matches a mentor to multiple mentees, as well as potentially expanding the mentor program to include more mentors, potentially from other year cohorts such as those born in 1966 or 1967 that are also close to retirement.

To help with the upcoming hiring and the mentorship, more queries or tables might be beneficial. First, it would be great to divide the outgoing, retiring employees by year, department, and title, in order to determine how many individuals per year are retiring. This will help the company determine how many people need to be hired and how many per year will require a mentor. Another table or query to run can be a more department specific query on qualified mentors to determine how many mentors are qualified by department and title. This will help plan which departments have the appropriate resources for the mentorship program, and which will need more attention. A final table would be to expand the qualified mentors table to include more years in order to increase the number of mentors to match the number of incoming mentees.