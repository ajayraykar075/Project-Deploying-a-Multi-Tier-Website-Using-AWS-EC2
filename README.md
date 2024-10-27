Project Overview
“I worked on migrating Company ABC’s product to AWS, specifically using Amazon EC2 and RDS to ensure high availability and scalability.”

Steps Breakdown
Launching EC2 Instances:

Objective: Set up the web application environment.
Action: I launched two EC2 instances with a suitable AMI that supports PHP, ensuring redundancy for high availability.
Enabling Auto Scaling:

Objective: Automatically adjust capacity based on demand.
Action: I created an Auto Scaling group with a minimum and desired capacity of two instances, 
allowing the application to handle varying traffic loads without manual intervention.
Creating an RDS Instance:

Objective: Use a managed database service for scalability and reliability.
Action: I set up a MySQL RDS instance, configuring it to meet the application’s database needs. 
This eliminated the overhead of managing the database server.
Setting Up the Database and Table:

Objective: Prepare the database for application use.
Action: I connected to the RDS instance and created a database named intel with a table data, 
ensuring that it was structured to hold the necessary application data.
Updating the Website Configuration:

Objective: Ensure the website connects to the new database.
Action: I updated the PHP application to point to the new RDS instance, ensuring seamless integration.
Configuring Security Groups:

Objective: Secure communication between instances.
Action: I modified the security group for the RDS instance to allow traffic from the EC2 instances 
on port 3306 (MySQL) and set the EC2 security group to allow HTTP/HTTPS traffic from anywhere for public access.
Challenges & Solutions
Scalability: Ensured Auto Scaling was properly configured to handle sudden traffic spikes, which could impact performance.
Security: Configured security groups carefully to balance accessibility with security, ensuring that only necessary traffic was allowed.

Conclusion
“This project not only enhanced the application’s availability and performance but also taught me a lot about AWS services and best practices 
in cloud architecture. I believe this experience has equipped me with the skills to contribute effectively in a cloud-based environment.”
