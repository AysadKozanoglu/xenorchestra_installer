# Xen-Orchestra (Community) Installer

Xen-Orchestra (Community) allows you to administer Citrix XenServer and XCP-NG as well as backup any VM's running on these systems. 

Confirm your VM's IP Address before starting the script so you know where to login to. 

The single line installer allows you to go from a bare-minimal installation of Ubuntu to fully operational. Run the following steps from a root shell. 

    sudo bash
    <password>
    sudo curl https://raw.githubusercontent.com/Jarli01/xenorchestra_installer/master/xo_install.sh | bash
    <password>
    
The default username and password are applied, admin@admin.net and admin for the password
    
If you don't want NFS capabilities run "sudo apt-get remove nfs-common".

* Do not use LAMP
* Optional to enable SSH access/highly recommended

