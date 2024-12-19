# Start-and-Stop-EC2-Instances-at-specific-time-of-a-day-using-CloudWatch-and-Lambda---Assignment

AWS Administration  
Monitoring Logging and Remediation

**Problem Statement:  
**In the realm of modern business, harnessing cloud technology is indispensable for flexibility and cost-effectiveness. However, a pressing challenge arises as organizations leverage services like AWS, particularly the need to ensure optimal utilization and cost efficiency.

This project addresses the need to start and stop AWS EC2 instances at specific times through automation. By leveraging CloudWatch Events and Lambda functions, instances will be dynamically activated or deactivated, aligning with business requirements and minimizing operational costs.

**Objectives:**

The project aims to establish a reliable and automated mechanism for starting and stopping AWS EC2 instances at predefined times. The objectives include leveraging CloudWatch Events to trigger Lambda functions, checking the current time, and executing instance start or stop actions accordingly. The goal is to enhance operational efficiency, reduce unnecessary expenses, and foster a deeper understanding of AWS automation techniques.

**Your focus in this project should be on the following:**

-   Grasping the concepts of AWS Lambda, CloudWatch Events, and EC2 instances.
-   Understanding how to schedule tasks using CloudWatch Events and trigger Lambda functions.
-   Implementing logic within Lambda functions to evaluate the current time and perform instance actions.
-   Verifying the successful execution of start and stop actions based on time triggers.

**Deliverables:**

-   Detailed documentation outlining the step-by-step process of setting up CloudWatch Events to trigger Lambda functions for automated instance start and stop.
-   A concise guide demonstrating how to create Lambda functions that check the current time and execute corresponding EC2 instance actions.
-   A sample CloudWatch Events rule definition showcasing the time-based schedule for triggering Lambda functions.

**Tasks/Activities List:**

-   Understand AWS Lambda and CloudWatch Events concepts.
-   Create a new Lambda function in the AWS Management Console.
-   Define CloudWatch Events rules to trigger Lambda functions at specific times.
-   Write Lambda code to determine the current time and act accordingly (start or stop instances).
-   Configure IAM roles to grant Lambda permissions for EC2 instance actions.
-   Test the CloudWatch Events rule and Lambda function by simulating instance start and stop events.
-   Document the setup process and include code snippets for reference.
-   

**Success Metrics:**

-   Achieve successful automation of starting and stopping instances based on scheduled times.
-   Confirm Lambda functions execute instance actions accurately and reliably.
-   Validate instances start or stop as per the defined time triggers.

**Bonus Points:**

-   Consider expanding the project to include dynamic scheduling options, allowing users to set custom start and stop times for specific instances. This enhancement would provide a more versatile and user-friendly solution.

**Submission Process:**

-   To showcase project completion, compile comprehensive documentation detailing the setup process, Lambda code, and CloudWatch Events configuration. Include screenshots or videos demonstrating successful instance start and stop actions based on time triggers.
