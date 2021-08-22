# Python CGI (App Install Automation)
 WARNING: This is ```just for fun project```, it automates the installation and uninstallation of various linux softwares using web-browser. Uses the minimal requirement of python-cgi for the implementation. However, the project is just for demonstration not for implementation practically as it makes your system vulnerable at port 80 (http) by giving apache2 created user ```www-data``` sudo priviledges.

## How to use:


1. Refer https://techexpert.tips/apache/apache-enable-python-cgi/ for installing and enabling python-cgi.
2. I have used 2 apps i.e. elinks and stress for demonstration of this automation project.
3. Install all the requirements from ```requirements.txt``` file.
4. Paste both ```test.py``` and ```script``` at the path ```/usr/lib/cgi-bin/```
5. Warning: Not recommended step, goto file path ```/etc/sudoers``` and give ```www-data``` permission to get sudo priviledges with no-password
6. Restart the apache2 server and use the address ```http://localhost/cgi-bin/test.py``` in web-browser

## Screenshots:


![](img1.PNG)

**************************************

![](img2.PNG)

**************************************



