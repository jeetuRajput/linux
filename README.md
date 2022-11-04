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

  <h1>SSH LOGIN </h1>
  First ping as well <br/>
  window to linux  <br/>
  linux  to window  <br/>
  
  #### Some time linux machine not ping window machin due to window firewall so just open CMD OR Powershell as adminstrater and paste it below command it will work
  
  <h1>netsh advfirewall firewall add rule name="ICMP Allow incoming V4 echo request" protocol=icmpv4:8,any  dir=in action=allow</h1>
  
  Now How to connect connection with SSH 
  
  Start SSH conection </br>
  
  <h1>sudo service ssh start</h1>
  
  You can check status of ssh</br>
  
  <h1>sudo service ssh status</h1>
  
  just type 
  
  <h1>ssh target-machin-ssh-username@target-machin-ip </h1>
  like ( ssh jeetu@192.168.0.1 )
  
 And passwd for login</br>
 
 ![image](https://user-images.githubusercontent.com/81432466/199922771-576d8fd5-5a92-44e2-aa60-5d3c4943b0c7.png)


  

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
