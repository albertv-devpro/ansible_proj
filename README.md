# ansible_proj
this setup was carried out in my linux Machine. i used my Linux machine as a control node deployed a webserver and a DB server on via VMware workstaion player. 
this setup was done to understand the configuration management process with ansible.
[websevers]       #CentOS deployed on this server--managed node
 COserver-1
 [DBserver]       # Ubuntu OS deployed on this server--managed node
 UBserver-2

 [Control machine]  # control machine with centOS AND anisble is installed
  myserver1
 
 Problem: i couldn`t installed packages on this managed nodes despite sucessfuly pinging the managed nodes from the controlmachine.
 
