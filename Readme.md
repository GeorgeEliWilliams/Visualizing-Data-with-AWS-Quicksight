# AWS Data Visualization Project with QuickSight

## Project Description:
This project demonstrates how to visualize data stored in an S3 bucket using AWS QuickSight. The dataset includes a Netflix.csv file and a manifest.json file. The steps include setting up an S3 bucket, configuring QuickSight, and creating insightful visualizations.

## Prerequisites
* AWS Account
* Basic knowledge of AWS services
* Data files: Netflix.csv and manifest.json

## Steps

### 1. Setting Up the S3 Bucket
* Navigate to the S3 service in the AWS Management Console.
* Click on "Create bucket" and provide a unique name.
* Select the region and configure settings as needed.
* Click "Create bucket."

Upload Data Files:
* Click on the bucket name you created.
* Click on "Upload" and add the Netflix.csv and manifest.json files.
* Click "Upload" to confirm.
![files uploaded](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/4710eb49-732c-4878-b241-67ab03d539ac)


### 2. Configuring AWS QuickSight
* Sign Up for QuickSight:
* Navigate to QuickSight in the AWS Management Console.
* Click on "Sign up for QuickSight."
![sign up for quicksight](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/dcd2f10b-960d-480b-a2e6-c8432d003eb3)
* Choose a subscription plan (Standard or Enterprise) and complete the setup.
* Enter your details for your QuickSight account - make sure the email you use is the same email for your AWS account.
![setting up quicksight](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/9eeeaca0-0ccb-4356-aed5-cb96619a6b42)
* Select Amazon S3.
* Select Select S3 buckets.
* Tick the box for the S3 bucket you created.
* Select Create.

### 3. Connect your S3 bucket to Amazon QuickSight

Create a Data Source:
* In QuickSight, go to "Manage data" and click "New data set."
![select datasets](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/0dbee81f-84c3-403d-8670-f918efcee79a)
* Select "S3" as the data source.
![select s3 from datasets](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/9a342c0c-7059-4f61-a29f-c3e6cad9a899)
* Provide a name and specify the S3 bucket path where the data files are stored.
![select the s3 bucket you want qs to access](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/36c8026f-9838-4de4-aa0c-b6a85e3c4367)
* Choose the authentication method and click "Create data source
* After creating the data source, select the Netflix.csv file.
* Enter the S3 URL to your manifest.json file.
* Select Connect
* Click "Save & visualize" to import the data into QuickSight.
![finish dataset creation and click visualize](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/25d9c597-61d5-4344-963d-6741244cf03a)

![after clicking visualize, seect create](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/22a70e42-f169-4146-ad43-51a280063389)

### 4. Creating Visualizations
![lets make visualizations](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/e20b2eac-e622-463c-b899-14ec3a2c7277)

* Use the drag-and-drop interface to create visualizations such as bar charts, line charts, and tables.
* Customize the visualizations by adjusting fields, filters, and formatting options.
* Number of Movies/TV Shows by Release Year
* Number of Movies vs TV Shows by Release Year
* Number of Thrillers, TV Comedies, Action & Adventure
* Number of Thrillers, TV Comedies, Action & Adventure (released ≥ 2015)
* Number of Titles Added by Date

#### Publish Dashboard:
* Once your visualizations are ready, click "Share" and then "Publish dashboard."
* Provide a name and description for the dashboard.
* Configure sharing settings and click "Publish."
![publish dashboard](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/19f59dc8-9e25-41b4-a441-396845c98505)

![published dashboard](https://github.com/GeorgeEliWilliams/Visualizing-Data-with-AWS-Quicksight/assets/103576454/a5d5979d-201f-4fd6-a66f-b7a00dc55f4d)


