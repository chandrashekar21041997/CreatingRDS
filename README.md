1)Launch free tier postgres RDS instance and have hands-on. Try creating different db's, users

Login in AWS Account and search for RDS click on it

Create RDS DataBase:-

![Screenshot (397)](https://user-images.githubusercontent.com/119240540/216385969-f33c17b2-27e5-4445-941d-8a669264edd2.png)
Click Standard create 

Engine options
SELECT
PostgreSQL

Templates
free tier 

![Screenshot (398)](https://user-images.githubusercontent.com/119240540/216386548-5038958e-5329-44e7-8e09-c327a6f91b5c.png)

Settings

DB instance identifier
chandrashekar-guvi

Master username
postgres
Password: As Given



![Screenshot (399)](https://user-images.githubusercontent.com/119240540/216386933-772e305a-74b7-46e4-821d-d7b614e22c32.png)


Instance configuration

![Screenshot (400)](https://user-images.githubusercontent.com/119240540/216387472-7477bb55-128c-4727-b90f-1c2f1f9ec2ab.png)

Storage
now am taking general purpose

Allocated storage
20
am disable for Storage autoscaling its is usefull to production
![Screenshot (401)](https://user-images.githubusercontent.com/119240540/216388061-585f59b7-972e-4bda-be42-d9ca3bb725dd.png)

Connectivity

Don’t connect to an EC2 compute resource

![Screenshot (402)](https://user-images.githubusercontent.com/119240540/216389036-764bd962-874b-4491-a8be-4e1a73b735de.png)

Public access Yes

![Screenshot (403)](https://user-images.githubusercontent.com/119240540/216389164-36988224-bd3e-4877-8176-95b05cc3635f.png)

Database port
5432


Monitoring
![Screenshot (404)](https://user-images.githubusercontent.com/119240540/216389528-c0e56fba-b4e9-4a90-8fa7-63d29a4d7cc9.png)

Additional configuration




![Screenshot (405)](https://user-images.githubusercontent.com/119240540/216389691-ad9ef474-033e-4d3b-817b-0811bd3ab944.png)

Click Create

after createing database 

and download table pluse 

after download and install table pluse check the connection is ok or not 

name: you given any name 

Host in endpoint which copy and paste

in tabke pluse tool
and port is defalut 5432
![Screenshot (406)](https://user-images.githubusercontent.com/119240540/216392133-73eef16f-3619-4147-9a53-7d847a04b8c8.png)



![Screenshot (407)](https://user-images.githubusercontent.com/119240540/216392491-0a31aaf1-155a-4b6f-91b3-db3d66d4bbf6.png)


and conncet it and create a databse and 

any if Create DB 

![Screenshot (408)](https://user-images.githubusercontent.com/119240540/216392868-3a5d5ea1-c1ad-4b87-a57b-58b71560c589.png)

Created DB name Ecomm

![Screenshot (409)](https://user-images.githubusercontent.com/119240540/216392951-37428ad4-196e-4020-9d10-bf676f0f0810.png)

Drop the DB also


![Screenshot (410)](https://user-images.githubusercontent.com/119240540/216393420-ef02516d-d73a-4399-a9e0-ef202948c597.png)


lauching EC2 UBUNTU

Installing 
sudo apt-get install postgresql


![Screenshot (411)](https://user-images.githubusercontent.com/119240540/216395260-0795d65e-9112-40ef-93f2-66e501dbf4b4.png)

psql -h chandrashekar-guvi.cb9ruul1tckh.ap-south-1.rds.amazonaws.com -U postgres -W
Paswword 
Login

![Screenshot (412)](https://user-images.githubusercontent.com/119240540/216396566-de0b9a55-4eda-40a1-a0ea-ffbe5746170e.png)


![Screenshot (413)](https://user-images.githubusercontent.com/119240540/216396787-adabde52-e42f-4886-84bb-8ca3decec6ed.png)

Createing database

CREATE DATABASE EcommGuvi;

![Screenshot (414)](https://user-images.githubusercontent.com/119240540/216397146-4173471d-dd75-416c-89a6-726841ec40df.png)


