# folder-builder
Scripts for building a folder structure used by sales and engineering.  When a new job is enter this script will build out the job directory and append the job number to each folder and file.


For example, the directory template below:

XXXX Job Name
    .
    .
    ...XXXX Calculations
    ...XXXX Schedules


becomes this directory for job 1234

1234 Job Name
    .
    .
    ...1234 Calculations
    ...1234 Schedules
    
The scripts walks down the enitre directory each creates a new folder and file for every folder and file in the template.  The engineering manager can change the directory template, add or remove files and the script will always works.

A similair script is used for sales quotes, but is much simpler because the directory structure is simple.
