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






<img src="https://github.com/jeetuRajput/linux/blob/main/image.png"/>
