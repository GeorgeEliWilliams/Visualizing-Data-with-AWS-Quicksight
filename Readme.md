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

### 2. Configuring AWS QuickSight
* Sign Up for QuickSight:
* Navigate to QuickSight in the AWS Management Console.
* Click on "Sign up for QuickSight."
* Choose a subscription plan (Standard or Enterprise) and complete the setup.
* Enter your details for your QuickSight account - make sure the email you use is the same email for your AWS account.
* Select Amazon S3.
* Select Select S3 buckets.
* Tick the box for the S3 bucket you created.
* Select Create.

### 3. Connect your S3 bucket to Amazon QuickSight

Create a Data Source:
* In QuickSight, go to "Manage data" and click "New data set."
* Select "S3" as the data source.
* Provide a name and specify the S3 bucket path where the data files are stored.
* Choose the authentication method and click "Create data source
* After creating the data source, select the Netflix.csv file.
* Enter the S3 URL to your manifest.json file.
* Select Connect
* Click "Save & visualize" to import the data into QuickSight.

### 4. Creating Visualizations
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

