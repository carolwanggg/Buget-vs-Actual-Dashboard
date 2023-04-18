# Buget-vs-Actual-Dashboard

1. Objectives:

Build a dashboard to update the budget vs Actual sales, demonstrate the variance analysis to show the differences betweet actual and budgeted sales by project category.
Presenting this dashboard to senior manager and project manager for them to capture the key infomation.

2. Dataset

I have three different sources of info:
Budget: the info we prepared and discussed together with project manager/budget owner,including phasing of budget(month), project code(ID) and budget amount.

Project Management: the info stored in SAP cloud, including project type(category),project id and projet name.

Sales: sale amount,project id and date.

3. Model

Based on the dataset I have, I recognized the primary key/foreign key in each table and build the relationship model.

To better use the date function, I created also the table date dimension.

![image](https://user-images.githubusercontent.com/129491801/232889878-5fff55c3-aced-49bf-93d1-db917f4f03c6.png)


4.Design

I design and build the interative POWER BI dashboard to present to the senior managers and project managers.

![image](https://user-images.githubusercontent.com/129491801/232890099-7177272e-d02f-4cb5-a2df-3f5d298b2894.png)


I added the project tooltips and budget tooltips for present more details.

![image](https://user-images.githubusercontent.com/129491801/232890387-f7a4c7ce-818e-4937-8012-ebf35a61240b.png)

you can see the variance of budget breakdown by month, I use the conditional formating also for the different colors.


![image](https://user-images.githubusercontent.com/129491801/232891303-785ccfb5-7dc7-412e-be63-807f2968b0aa.png)



5.Summary

The dashboard improved the efficiency of reporting workflow, presenting the key metrics and info to senior manager.
