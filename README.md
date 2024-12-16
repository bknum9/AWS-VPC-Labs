# AWS-VPC-Labs
<h2>Creating a Basic VPC and Associated Components in AWS</h2>
<p>In this hands-on lab, I created a VPC with an internet gateway, as well as create subnets across multiple Availability Zones. This lab was completed in a sandbox environment through A Cloud Guru. Link for the youtube video: https://youtu.be/F3JuD73ZKeI</p>

<h2>Lab 2</h2>
<img width="1434" alt="vpc2" src="https://github.com/user-attachments/assets/a9ff8796-dc1e-4fe9-8465-c1686a224531"></br>
1 - Creating a private and public subnet for the vpc created and placing them in two different AZs
<img width="1434" alt="vpc3" src="https://github.com/user-attachments/assets/c9ed498e-cf62-44db-87b1-d6a8be881464"></br>
2 - Creating an internet gateway and attaching it to the VPC
<img width="1434" alt="vpc4" src="https://github.com/user-attachments/assets/96b387b8-af19-4cc4-8f4a-032088f3a1f1"></br>
3 - Creating route table, edited the route to allow internet traffic into the internet gateway and associated it with the public subnet
<img width="1434" alt="vpc5" src="https://github.com/user-attachments/assets/f6b06be2-4dec-488e-9b50-a2e365dd7b5f"></br>
4 - Launched two EC2 instances one for the private subnet and one for the public subnet
<img width="1434" alt="vpc6" src="https://github.com/user-attachments/assets/4ff24cc0-b0d4-4e07-8b34-d6cb529870d0"></br>
5 - Using SSH to log into the EC2 instance in the private subnet from the public subnet
<h2>Working with AWS VPC Flow Logs for Network Monitoring </h2>
<img width="1438" alt="vpc1" src="https://github.com/user-attachments/assets/1a591af6-ac9b-4ea6-8c17-4c726063fdfb">
1- Creating a flow log for our VPC
<img width="1438" alt="vpc2" src="https://github.com/user-attachments/assets/6f1f4435-ae97-4e72-8165-87217567ec1b">
2 - Making a log group for our VPC flow logs
<img width="1438" alt="vpc3" src="https://github.com/user-attachments/assets/b1e0f840-8bae-4ace-862b-466628a55ff0">
3 - Reviewing log streams in CloudWatch
<img width="1438" alt="vpc4" src="https://github.com/user-attachments/assets/8f44bfac-684b-4f54-9bba-5aa7e1340db9">
4 - Made metric filter to filter out logs that point to ssh rejections
<img width="1438" alt="vpc5" src="https://github.com/user-attachments/assets/32054f2d-b71d-463a-922f-7ab13848cd28">
5 - Looking through flow logs that have been saved to an S3 bucket for long term storage

