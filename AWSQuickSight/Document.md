# **Visualize data with QuickSight**
![final dashboard](https://github.com/user-attachments/assets/f96107dc-a99b-4000-b298-f69a591307db)

### **What is Amazon QuickSight?**
Amazon QuickSight helps you analyse data and create visualisations easily. Today we're going to analyse a huge dataset of Netflix shows and movies to create a dashboard that extracts all the juicy insights.


### **How I used Amazon QuickSight in this project**
I used Amazon QuickSight in today's project to create interactive dashboards by connecting to an S3 data set, applying filters, and visualizing key insights through bar and line charts.

## **Upload project files into S3**

S3 is used in this project to store two files, which are 1.manifest.json 2.netflix_titles.csv


I edited the manifest.json file by its URL. Itʼs important to edit this file because the URL present in the old file did nit contain my name in it

![uploading files in S3 bucket](https://github.com/user-attachments/assets/036af14f-8841-4e24-8102-2b47e1e1bf6e)

## **Create QuickSight account**

Creating a QuickSight account cost no money. It's free.


Creating an account took me about 2 minutes.

![QuickSight Account Created](https://github.com/user-attachments/assets/41eb5b83-8c0e-4dcc-b896-63b4c4d96495)

### **Download the Dataset**

I connected the S3 bucket to QuickSight by visiting new dataset tab


The `manifest.json` file guides Amazon QuickSight to your data's location and structure. It ensures QuickSight understands various data formats, acting as a map for efficient data reading.

 ![S3 Connection Setup Pannel](https://github.com/user-attachments/assets/5916bd63-b5f0-4da4-af4f-ad073bd26634)

## **My first visualization**

To create visualizations on QuickSight, I added a data set by selecting "New Data Set" and choosing your data source (e.g., S3). Then, click "Add visual," choose your visual type, and drag fields from the data set into the visual pane.


The chart/graph shown here is a breakdown of TV shows vs movies for every year.


I created this graph by dragging and dropping release year label in the Y-axis heading and type label in Group/Color heading.

![Visualization of dataset](https://github.com/user-attachments/assets/5bcd60ef-14de-440d-840b-3f430d784a0c)

## **Using filters**

Filters in QuickSight are useful because they allow you to refine and focus your data, enabling dynamic analysis and personalized visualizations based on specific criteria.


Here I added a filter by labels which are type, date added, listed in and the listed in give us the special features to filter the data.

![filters visualization](https://github.com/user-attachments/assets/23861a24-f349-476e-a972-1275ec0340b1)

## **Setting up a dashboard**

As a finishing touch, I gave a name to all of those charts which are visible in the dashboard.


To export your dashboard as PDF, we have to click on the export tab on the top right hand corner.

![final dashboard](https://github.com/user-attachments/assets/3316793b-31d6-4f33-9c51-70010a738205)

