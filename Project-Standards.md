1) Using Lab AMI, we will provision "t3.micro" spot VM's
2) They are expected to have "B59-Sg" [ A security group that allows all ports from the internet ]
3) Each and every VM is expected to have the Application Component Name.

    AMI To Use  : DevOps-LabImage-RHEL9
    Region      : N.Virginia
    Credentials : ec2-user/DevOps321

Always remember, when an application is dependent on Database, make sure the Database comes first and then applicaiton. If not, application looks for the database and won't start.

Proxy vs Reverse Proxy:
Purpose of reverser proxy:
    1) Hides the true identity of the needed servers
    2) Sends the reqeusts to the backend servers with confidentaility.
    3) Webservers have the capability to reverse proxy
    4) Typically Frontend will reverse proxy the backend servers

Assignment: 
    1) SQL DB vs NoSQL DB 
    2) What is Column DB
    3) What is Queue Manager