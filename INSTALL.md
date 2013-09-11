ENVIRONMENT SET UP
===================

To host SNAPP at your institution you will be requiring  

Installations
--------------------
Tomcat 7 
------------------
1) Apache Tomcat - http://tomcat.apache.org/
  Note: Always do a fresh install of Tomcat
  Note: Windows users should ensure that there are no spaces in the complete tomcat path as this causes errors with JSF tools in Sakai
  GOOD: C:\tomcat\, C:\SNAPP\installs\tomcat\
  BAD: C:\program files\tomcat\, C:\opt\apache tomcat 7.0.1\
2) Extract the files to C:\Tomcat 
3) Set environment variable: CATALINA_HOME=/Tomcat. Add $CATALINA_HOME/bin to PATH

Install WAMP server
---------------------------
1) Download the WAMP stack from http://www.wampserver.com/en/ . Run the .exe file
2) Run start Wampsever(wampmanager.exe)

Hosting SNAPP on server
---------------------------
SNAPP
--------
1) Download the SNAPP source available in github https://github.com/sandeepmjay/SNAPPSakai-Beta. 
2) Place this folder in the webapps folder of Tomcat.
3) Start Tomcat by running the C:\Tomcat\bin\startup.bat.
4) Open Firefox and enter the URL http://localhost:8080/SNAPP/index.html
5) Right click on SNAPP V2 Beta link and bookmark the link.


File Saver
-----------
1) Download the FileSaver project from github https://github.com/sandeepmjay/SNAPPSakai-Beta. 
2) Place it in C:\wamp\www\ folder.


Deploying SNAPP on Forums
-------------------------------

After these steps you can share the bookmarklet with faculty, students, researchers and they should be able to run it on expanded forums.







  
