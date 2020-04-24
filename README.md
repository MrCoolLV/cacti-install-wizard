Cacti server setup wizard <br>

this script requires git and unzip<br>

To use the script <br>
yum install git unzip -y <br>
git clone https://github.com/MrCoolLV/cacti-install-wizard.git <br>
cd cacti-auto-install <br>
chmod +x cacti-install-wizard-centos.sh <br>
./cacti-install-wizard-centos.sh <br>
RUN THE SCRIPT AS ROOT!!


The script also works on RHEL however you MUST enable EPEL prior to running the script and ensure its working
to enable RHEL EPEL reports you can use the following command 
```
yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
```


- features are

-download either chosen or latest version of cacti<br>
-autoconfigure database either with defaults or chose credentials<br>
-auto tunes MariaDB using cacti recommended settings<br>
-auto-populates cacti database<br>
-downloads all needed packages for cacti install<br>
-asks if you want to install spine if so it will automatically compile it<br>
-adds system user and assigns permissions to folders<br>
-downloads and installs plugins<br>

TODO 

Debug
Add more plugins to download option<br>
add option to select specific plugins from list<br>
Document script


BUGS

Please let me know!


Check out my video tutorial on using the script !


[![Video Tutorial ](http://img.youtube.com/vi/koUcuQT0KIU/0.jpg)](https://youtu.be/koUcuQT0KIU "Video Tutorial")


