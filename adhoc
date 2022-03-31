
Reboot your company servers in parallel forks at a time. For this we need to set up SSH agent for
connection.
$ ssh – agent bash
$ ssh-add~/.ssh/id_rsa
To run reboot for all servers.
$  Ansible abc  -a  “/sbin/reboot”
Transferring file to many servers/machines
$  Ansible abc  -m copy  -a “src   = /etc/yum.conf  dest =  /tmp/yum.conf”
Creating a new directory
$  Ansible abc  -m file  -a “ dest =  /path/user1 /new mode =777  owner = user1  state = directory”
 Deleting whole directory and files
$  Ansible    abc  -m file  -a  “ dest = /path/user1/ new state =absent”
The  below command is used to check  the package is install or  not .
$  Ansible  abc  -m  yum  -a  “name  =  demo-tomcat-1  state = present”
The  following command check the package is  not installed.
$   Ansible  abc  - m yum -a  “name = demo-tomcat-1 state =absent”
The following command check the latest version of package is installed.
$  Ansible  abc -m yum-a  “ name =demo-tomcat-1  state = latest”
 Facts can be  used for implementing conditional  statements in playbook.you can find adhoc information of all your facts through the following Ad-hoc command.
$  Ansible  all- m setup
Deleting  a file
-name:  Ansible delete file
Deleting multiple files by  iterating with Ansible loop.
-name:  Ansible  delete  multiple
Ansible delete a directory/folder.
-name: Ansible delete directory
		

