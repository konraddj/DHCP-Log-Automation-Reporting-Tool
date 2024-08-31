# DHCP Log Automation & Reporting Tool #
## Project Scope ##

This project aims to write a simple log file process for DHCP logs from a production server Ubuntu based on client networks including CCTV.

Each sentence of the log is analyzed to extract data fields such as:
- IPv4 address
- MAC address
- hostname
- computed OUI OEM information
#
The assumption of the project is to write the code clearly and cost-effectively and to practice its functionality in separate modules.
#
The generated list with interesting nodes was saved in a CSV file, keeping in mind a readable style, without duplicating data.
#
## Project composition ##
The project comprises four categories:
1.  Structure
2.  Documentation
3.  Styles
4.  Functionality

The project should fill these categories with the best effort as intended.
#
![img.png](device.png)
#
## The structure of Project files ##
An important aspect of the project was to create a directory structure suitable for the files created in this work. "main.py" as the main executable, imports functions and packages from the source directory. The tests focused on the functions or code snippets related to the project.
#
>More detailed information about the project can be found in the Documentation directory.
#
