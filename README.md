# FSDI_Project: 
Task manager site to organize incoming work as requests, current status, and completed/archived tasks in a development and production laboratory environment. Also, a data management section to centralize the data that is created when performing these tasks.

##Who is the user?
Engineers, managers, and technicians of various ages/technical backgrounds
##Features:
>A main page that allows anyone to see current jobs, without logging in
>User creation/admin panel to add/modify jobs
>Simple request form to add jobs to queue for non registered users. Maybe add a FAQ section about the resources available and answers to most common questions about the lab(eg. Fixture drawings, equipment capabilities, requirements, etc)
>Simple file uploader that allows users to add raw data(analog/digital signals data, reports, photos, videos, etc) to database with unique tags
>Create a report generator page for specific test types. This will allow for standardization of data and provides real time analysis of test data. Will be able to consolidate scripts saved on several different engineers' workstations and can eliminate the delay in confirmation caused by out of office/off hours/and overloaded engineers.
>Allow data to be visualized to analyze trends, fail criteria, 
>Allow importing to centralize data from different sources(eg. svn, jira, solumina, bender, etc) based on part number or work order.
>Create a QR code generator page to link to a dataset
>API to send out job data to different programs

##User Models
###Engineers(requesters): 
>Create new requests to get product tested through the lab.
>Need a simple FAQ to learn the process of getting their product through the lab. This will help engineers from different departments avoid the repetitive meetings describing the process.
>FAQ is a simple resource for requirements, schedule/availability for engineers that don't know where to start
>Need a way to visualize the data(eg. Test summary/reports with pass or fail criteria to avoid misinterpretation of data) and a resource to collect all data for final summary
###Managers(manage schedule/technicians/priorities):
>Need a way to track incoming jobs, view current schedule, and view hold/failed product so they can focus on finding a resolution 
>Need to be able to go back and reference old jobs to address any issues that were missed or performed incorrectly
>Need admin privileges to manage assigned users and rearrange tasks based on priority from upper management/schedule
###Technicians(users):
>Will use to find current work assigned, communicate issues, and comment current status during shift handover
>Be able to complete, claim, or place jobs on hold
>Need a simplified summary of requirements(functional, thermal, vacuum, shock, humidity, and vibration requirements) to test against, know what specialized equipment/hazards are present, and if engineering support is needed during testing. 
>Need to know point of contact for issues/questions
>Need a simple place to add raw data, photos, videos, and reports linked to a specific job
>Need a way to view previous test configurations by searching for a part number or work order. Photos and test data are a valuable asset to compare against to filter out any issues and identify out of family conditions
