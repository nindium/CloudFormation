Step by step description actions VPC template vpcbasic.json performs:
* line 2: Defines Template version
* line 3: Defines Template description
* line 4-13: Define parameters: values to pass the template at runtime:
    - line 5-8: Key pair for access to the EC2 instances
    - line 9-13: AMI to build EC2 instances
* line 14-172: Define Template Resources:
    - line 15-29: creating VPC1
    - line 30-53: creating public subnet for VPC1
    - line 54-77: creating private subnet for VPC1
    - line 78-89: creating Internet Gateway for VPC1
    - line 90-96: attaching Internet Gateway to VPC1
    - line 97-106: creating VPC2
    - line 107-123: creating public subnet for VPC2
    - line 124-140: creating private subnet for VPC2
    - line 141-147: creating Internet Gateway for VPC2
    - line 148-154: attaching Internet Gateway to VPC2
    - line 155-161: creating Public Route Table for VPC1
    - line 162-170: creating default route via Internet Gateway for VPC1
    