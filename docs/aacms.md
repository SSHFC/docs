# Introduction

The Attendance and Access Control Management System (AACMS) is a system designed to keep track of all official staff movements. 


## Who Benefits From The Attendance And Access Control Management System

- Human Resource Management Personnel
- Information Technology Officials
- Members of Management

## System Input

- Staff Daily Clock-Ins
- Postings from the Human Resource Management System 
    
## System Output

- Summary Attendance Report
- Summary Access Control Report
- Detail Attendance Report
- Detail Access Control Report
- Individual Deduction Calculation

## AACMS Module

Upon a successful sign in, a dashboard is displayed as shown in Figure 4.
Highlighted in <span style="color:red">red</span>, is the AACMS module.
![Figure 4](img/dashboard.png){ align=center }

In this instance, we will be looking at the AACMS module. This module helps generate various reports as outputs based on member/staff attendance. Clicking <span style="color:red">AACMS</span> in the dashboard or on the sidebar opens a portal that allows users generate various reports as shown in Figure 5.
![Figure 5](img/aacms.png){ align=center }

There are several options / reports that can be generated,using the options provided on the main page. Detailed and Summary reports, filtered by ``dates``, ``departments``.

Also included is an Access Tracking Module. This feature helps track staff movement withing the SSHFC premise.

![Figure 6](img/detailed.png){ align=left }
![Figure 7](img/summary.png){ align=right }

## Filtering Detailed Reports By Date

The detailed report can be filtered by dates. The filter generates information within a date range.
See Figure 8.
![Figure 8](img/date-detailed.png){ align=center }

Below is a sample, generated between the date range **1st to 27th of November 2021**
![Figure 9](img/detailed-result.png){ align=center }

## Filtering Detailed Reports By Department
A detailed report can also be filtered by department as shown in Figure 10 and 11. A list of departments are generated in a dropdown to make selection easier.
![Figure 10](img/detailed-branch.png){ align=left }
![Figure 11](img/detailed-branch-result.png){ align=right }
## Working With Reports

All reports come with certain functionalities, they are:

- Ability to export into pdf.*
- Ability to export into excel.*
- Ability to search by any of the fields in a multi-field search box. **
- Ability to perform basic sort functions: Ascending and Descending.***
- Ability to limit column visibility. *

The figures below point out these functionalities.

![Figure 12](img/workingwith.png){ align=center }

Output for Excel and PDF exports.

![Figure 13](img/excel-export.png){ align=center }
![Figure 14](img/pdf-export.png){ align=center }



## Reducing Columns
The Ability to Limit or Select visible columns is done by clicking the **column visibility** button and selecting out of the drop-down, options you want to make hidden.
See Figure below.
![Figure 14](img/column-visibility.png){ align=center }

## Filtering Reports By Name
Using the filter/ Search box. You can search for anything. See figure below.
![Figure 15](img/search.png){ align=center }

## Filtering Summary Reports By Date

This functionality is a similar process to filtering and attendance report by date. 

## AACMS Deduction

This functionality allows one with persmission to initiate the calculation of absentism of staff and place a monetory value to it. This value is then posted to payroll for deduction during the period for payroll run.

![Figure 16](img/1deductions.png){ align=center }

The drop down, under the AACMS module: ** AACMS Deductions** opens up a page that displays a daterange selector, allowing one with permission to select the range of dates for which deduction calculations are to be done. Next is to click ** Generate**.
Once this is done, a list is generated that has the list of staff and number of deductions calculated. The view deductions button becomes visible. 

![Figure 16](img/2deductions.png){ align=center }
Clicking on this button, cleans up the table and makes the deductions ready for posting to the individual deductions table in payroll.

![Figure 16](img/3deductions.png){ align=center }

On this page, the ** Post Deductions** and  ** Revert Deductions** become visible. Clicking on the Post deductions button completes the process. The revert Deductions button, reverts the process to the beginning.

![Figure 16](img/4deductions.png){ align=center }

If there are existing deductions in the individual deductions table ,the process will quit with an error. This will mean, the payroll has not been run.
After each run, the deductions table is cleared.

![Figure 16](img/5deductions.png){ align=center }