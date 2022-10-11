# AWS-Implementation-5450


This project is contributed by Yilin Yang, Jason Li, and me. In this project, we implemented AWS VPC, EC2, S3, RDS, Sagemaker, Cloudwatch, IAM, and security groups. A process summary can be found below:

We have completed our cloud computing project and met all of the success criteria. We set up a VPC first, loaded data into an S3 bucket, and built a flask server running in EC2 to process and analyze data.
After that, we set up a database on RDS and access the data from both the CLI and flask server to display the data and analysis result. The analysis results could help our client better understand the Iowa liquor market. Besides, we also set up a Python notebook instance in Sagemaker to analyze data. To ensure security and privacy, we modified a role in IAM to allow EC2 and RDS to access S3. We also set up security groups accordingly.
Also, we set up Cloudwatch to monitor CPU utilization and send alarms if CPU utilization is higher than we expected. For cost analysis, we compared our cost of cloud computing on AWS and Microsoft Azure. We found that AWS’s cost is significantly lower than Azure’s cost.
