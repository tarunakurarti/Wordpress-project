# tarun

# step:1

first make a director where u want to start your project code 

***code:*** **mkdir filename**

# step:2

then open new terminal then install both wordpress and mysql in the linix 


***command:***
**yum install mysql:5.7 -y**

***command1:***
**yum install wordpress:5.1.1-php7.3-apache -y**

# step3:

downlaod docker compose and activate it

***command:***
**sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose**

***---the above command will download the dowload compose ---***


***---after that use the following command to use it---*** 

***command:***
**sudo chmod +x /usr/local/bin/docker-compose**

# step:4

go inside the directory using cd

***command:*** **cd /filename**

# step:5

you will get inside the directory u have created

output of the above command will be like this

> @root86676:filename:# 
- like this but the way i shown will not be similar but the the filename u created will be on the side 

# step:6

create a yaml file

***command:*** **docker-compose.yml**

it open terminal as input window 
u wil get a black screen then click "I" on the keyboard to go insert mode 
copy my code to the terminal and then click ese on the keyboard and then press :wq
on the keyword it will exit the input command terminal

# step:7

run the command

***command:*** **docker-commpose up**

it runs the yaml file which is inside the directory then first know the ipaddress of ur system and use port number after it 

***example: 
192.168.47.97:8080***

like the above example the ipaddress will be 

# step:8
go to os and open the browser and type the ip address of urs as above then ur username and password as mentioned in code
then wordpress setup will come complete the setup and have fun

:+1:***that's it folks have fun creating the project enjoy 
if any problem regarding it contact me @kartheek1968@gmail.com***:shipit:

made by 
- TARUN
- KARTHEEK1968@GMAIL.COM

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

