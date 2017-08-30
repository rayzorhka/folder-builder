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
    
The scripts walks down the enitre directory and creates a new folder and file for every folder and file in the template.  The engineering manager can change the directory template, add or remove files and the script will always works.

The script for the sales quote folder is simpler.  It simlpy make a new directory tree for each new job.
