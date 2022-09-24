# NadiaAbdelmoaty
Project #1
Apache or NGINX Web Server on Google Cloud
the steps:

from your Cloud choose Compute Engine and from it select VM instances
click on CREATE INSTANCE
create your VM name and region
enable the firewall
then click Create
if your VM is done open the SSH
to install the Apache write:
sudo apt-get install apache2
then write Y to complete the installation
back to the VM , get the IP and open it.
you will see the defult page
to edit in the HTML file :
sudo nano index.html
to change the HTML file name:
cd/var/www/html/
sudo mv indexhtml  cloudh_academy
ls
cloud_academy  ------  (it changed)

