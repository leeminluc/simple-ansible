# An ansible project which deploys a simple apache website hosted by both frontend and backend autoscaling groups in which the traffic is routed by a load balancer.
![image](https://github.com/user-attachments/assets/7814f009-965f-4f06-b70c-ff3ef3686e22)

• This configuration uses AWS infrastructure.\
• The web deployment files are stored in AWS s3 bucket and being pulled from the ec2 instances.\
• The Ansible roles (common, frontend, backend) will execute their own set of tasks upon the creation of the ec2 instances.\
