# AWS Cloud

> 1. Create a VPC with CIDR 10.15.{8*team#}.0/22; no custom subnets.

![VPC](prajesh-screenshot/1.png)

- Using us-east-1 AZ

![AZ](prajesh-screenshot/2.png)

> 2. Start a EC2 (in default VPC of the region)
 a. Amazon Linux OS
 b. Use t2.micro instance (Free Tire)


![1](saroj-screenshot/1.png)

> c. Attach 10GB General EBS (detachable)

![2](saroj-screenshot/2.png)

![3](saroj-screenshot/3.png)

![4](saroj-screenshot/4.png)

![5](saroj-screenshot/5.png)

![6](saroj-screenshot/6.png)

![7](saroj-screenshot/7.png)
 
> d. Should be publicly accessible
  e. Access the the EC2 via SSH

![SSH](screenshots-openvpn-bijay/pem%20file.png)


> f. Install OpenVPN package inside the EC2

![Amazon-linux-extras](screenshots-openvpn-bijay/amazon-linux-extras.png)

![install openvpn](screenshots-openvpn-bijay/install%20openvpn.png)

![installation complete](screenshots-openvpn-bijay/installation%20complete.png)
