# linux
basic to advance

<h1> 1 <br/> How to add user in linux</h1> 

sudo adduser jeetu ( iske baad enter krna hai)<br/>

###for check

first go to root directory

cd /<br/>

sudo cat /etc/passwd<br/>

Some time it will show error msg like (<username> is not in the sudoers file)<br/>

  <h1>##Solution >> login root as command </h1><br/>

su root <br/>
nano /etc/sudoers<br/>

Scroll down until you find root  ALL=(ALL)  <br/>
ALL and add the following line below it. Replace <username> with your actual user name.<br/>
  
your username ALL=(ALL) ALL<br/>

then reboot command use<br/>

then again login . Now you can just type <br/>

cat /etc/passwd <br/>
  
  
===========================================================================================================================  

<h1> 2 <br/> How to give file permission in linux </h1> 

![image](https://user-images.githubusercontent.com/81432466/199907251-a73ab7f1-2c5f-4ab7-a474-51ccef2c6624.png)

But when i changed permission 

<h1>chmod +444 jeet.txt (4 means only read )</h1>

![image](https://user-images.githubusercontent.com/81432466/199908247-e68453fe-c584-45c3-bef4-8a876f130c0c.png)

<h1>chmod +777 jeet.txt (7 means only read,write,exucate )</h1>

![image](https://user-images.githubusercontent.com/81432466/199909210-081e7fcd-6eb8-42ec-8d12-6a9ed6bc143e.png)

<h1>Linux permisson chart </h1>

<img src="https://github.com/jeetuRajput/linux/blob/main/image.png"/>


=============================================================================================================================================
