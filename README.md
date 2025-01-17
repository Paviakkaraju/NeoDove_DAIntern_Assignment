# NeoDove_DAIntern_Assignment

## Approach:
● SQL Queries for the questions were written using Python and PyMySQL. 
● Initial data exploration was done in Python to check for any anomalies and data inconsistencies.  
● The app_settings column in the org table was normalized from JSON format into separate 
columns.  
● A new database was created and all the tables were imported through Table Data Import Wizard 
in mySQL workbench.  
● A PyMySQL connection was established to query the results. 

## Questions:
1. Find the average number of calls made by a user in an org. 
*Expected Output*:
Org ID, no. of users, avg calls made by an user 

2. Find out the number of users  who have at least 3 connected calls in a month and who are given 
permission to see the contact number of the lead on a monthly basis.
*Expected Output*:
Month, Active Orgs, Users with atleast 3 connected calls and permission to display contact number

3. Find the number of orgs that have enabled follow ups mandatory permission for their 
users. Also find and compare the number of calls made by orgs that have enabled the 
permission versus the orgs that have disabled the permission.
*Expected Output*:
No of orgs enabled permission, Average no of calls made, No of orgs disabled permission, Average no of calls made

4. Find out the number of active orgs that have enabled or disabled each of the app settings listed in the Org 
Table.
*Expected Output*:
app_setting,                next_followup_mandatory,   enable_automatic_dialling   
view_leads_of_other_users   
automatically_dial_after_sec   
display_start_calling_button   
no of orgs enabled 
no of orgs disabled 
display_contact_number_on_lead 
