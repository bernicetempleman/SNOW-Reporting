# SNOW-Reporting

ServiceNow reports are visualizations of your data that you can share with users on dashboards, export to PDF, and send via email.

ServiceNow reports can be lists, charts, or calendar-based views of data in a particular table. The ServiceNow system also offers a range of predefined reports that pertain to applications and features like incident management and service catalog requests. If none of the predefined reports meet your needs, you can create your own reports. Use reports on homepages to display key information to different users. You can also publish reports to a URL that can be emailed. 

In ServiceNow reporting, you can control the following aspects of reports: 

Report Visibility
Report Types
Report Generation
Report Output formats

You can generate ServiceNow reports manually or according to a schedule!
## Visibility

You can control who sees reports by making them:
 
Globally visible to all users. 
Visible only to the report creator. 
Visible to one or more specific users. 
Visible to one or more specific groups. 

Report visibility controls which users can access individual reports.


ACLs control access to the underlying table data. List reports require the reporting user to satisfy ACLs on the target table to view records in the list. Users without sufficient permissions may see filtered list reports. 


## Types of Reports 
You can generate the following types of reports, organized by category:
	 
List
Time Series Chart
Line
Column
Area
Spline
Column and Bar charts
Bar
Pareto
Histogram
Pie and Donuts
Pie
Donut
Semi-donut
Dials
Speedometer
Dial
More


## Generation
You can generate a report manually at any time. These on-demand reports are useful for capturing information at the moment, such as the number of incidents assigned to you right now.

You can also schedule reports to generate on a regular basis.
The charting engine you use depends on the version of the ServiceNow platform you are running. 

## Output format
You can publish reports in the following output formats. You can schedule all of these reports for regular export. 
![image](https://user-images.githubusercontent.com/12488769/148379992-c72576a8-1f83-40b5-9c67-a7b92500e6cf.png)

## Report designer and builder
The Report Designer provides a guided flow for report creation. Selection of the data source, selection of the report type, configuration, and styling of the report are presented on successive tabs. The Report Builder provides most report creation functionality in a single panel.

Using the Report Designer, users can configure a report, preview it, iterate and adjust, then share it using the integrated Share panel.
The older Report Builder provides functionality for naming, selection of the data source, and configuration on one page. Style option selection is provided in a pop-up.

The Report Designer supports imported data sources and MetricBase Time Series reports, but the Report Builder does not.
![image](https://user-images.githubusercontent.com/12488769/148380235-b85dbe88-dfe5-4e47-b646-8a0871e8eb2f.png)

### Creation
![image](https://user-images.githubusercontent.com/12488769/148380281-c600b7fb-2523-4a42-8f84-0bafc7546151.png)

### Copy a report
Copying a report enables users who cannot create their own global reports to modify a global report, and then save a personal version of the report.
![image](https://user-images.githubusercontent.com/12488769/148380348-5e55c6fa-be42-43ed-9368-9546f7b07a49.png)
Navigate to Reports > View / Run.

 Click the arrow next to Save.



 Select Insert and Stay.



Creates a copy of the report that can be modified.![image](https://user-images.githubusercontent.com/12488769/148380373-b104c8cc-c587-4265-9737-7894020b0768.png)


### Delete a report
Delete reports that are no longer used.
![image](https://user-images.githubusercontent.com/12488769/148380402-88352ce2-52e9-4cce-b33f-aad1c656ee54.png)

 Navigate to Reports > View / Run.

 Select the report to Delete.

 When the report opens, click the Delete icon.

If you are using the Report Builder, click the arrow next to the Save button and select Delete

 Confirm that you want to delete the report.

 Result
The selected report is removed, and is no longer available to share, publish, or view.


