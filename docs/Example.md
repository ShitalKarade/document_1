---
layout: default
title: Example
nav_order: 8
---
# Creating Resource:
Creating a new resource in FactoMes
 *  Create resource: - Right-click on the FactoGrid project resource in the Project browser tree

![](../../assets/images/example/example-1.png)
{: style="text-align:center;"}

 *  After creating a resource, the screen will be appeared as below
 
![](../../assets/images/example/example-2.png)
{: style="text-align:center;"}
*  Note: It is essential to save the project after creating a transaction. Failure to do so may result in the resource not being available later

 *  At the top of the screen, user can select the “Site” and “Area” of their Enterprize from the given dropdowns

![](../../assets/images/example/example-3.png)
{: style="text-align:center;"}
*  Note: The table data will be displayed as per “Site” and “Area” selection

 *  In the left hand side, there is a tree node from which user can select the screen that they want to see. Equipment screen will be displayed initially by default(It can be changed as per Enterprize requirement)

![](../../assets/images/example/example-4.png)
{: style="text-align:center;"}

 *  In the right hand side, there are buttons for Add, Edit, Delete and Upload so that user can modify the data

![](../../assets/images/example/example-5.png)
{: style="text-align:center;"}

 *  After the user clicks on “Add” button, a popup window will be appeared on screen to enter the details as below

![](../../assets/images/example/example-6.png)
{: style="text-align:center;"}

 *  If any of the required field is not filled and clicked on “Save” button then the below error popup message will be displayed and after clicking on “OK” button, the “Add” popup screen will appear again with highlighted field which needs to be filled

![](../../assets/images/example/example-7.png)
{: style="text-align:left;"}
![](../../assets/images/example/example-8.png)
{: style="text-align:right;"}

 * While adding the data, If already existing ID entered and clicked on “Save” button  then the below error popup message will be displayed
 * Once the required fields are filled and clicked on “Save” button then the row selection will move to newly added row
 * After the user clicks on “Edit” button, a popup window will be appeared on screen to modify the details as below and only the editable fields will be enabled and others will be in disabled mode(which cannot be modified from userlevel).  
 * After the user clicks on “Add” button, a popup window will be appeared on screen to enter the details as below
 * Once the fields are modified and clicked on “Save” button then the selected row will get updated
 *	Note: It is essential to select the row in case of Edit and Delete actions
 *	After the user clicks on “Delete” button, a popup window will be appeared on screen to update the EffectiveEndDate as below
 * Once the EffectiveEndDate field is selected and clicked on “Save” button then the same will get updated in the selected row
 *	After the user clicks on “Upload” button, a popup window will be appeared on screen as below
 *	Once the user clicks on “Upload” button in the popup screen, the file explorer will get opened from where user can select the file for upload and then the user should click on “Import” button to upload the file
 *	User can also get File Template from the “Download Data Template” button and then they should fill the required data in it and upload the same file using “Upload” and “Import” buttons as above mentioned step
 *	Once the File is uploaded, user should click on “Validate” button and then the file will be displayed as below along with the status and then click on “Save” button to save the data
 *	While validating, if any errors then the below popup will be displayed and user should check the status to know an exact issue with the data
 *	The major purpose of this “Upload” button is to bulk upload the data which can save time and energy
 *	User can check the parent’s table properties in the child table(bottom table) by selecting the row from the parent table
 *	Based on the parent table’s row selection, data will be displayed in the child table
 *	User can perform the actions like Add, Edit, Delete and Upload in the child table also as same as Parent table
 *	User can perform search on both the parent table as well on the child table

