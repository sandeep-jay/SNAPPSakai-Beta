ENVIRONMENT SET UP
===================

To host SNAPP at your institution you will be requiring  

Installations
--------------------

<b>Install/Verify Java</b>

1. Download Java from http://www.oracle.com/technetwork/java/javase/downloads/index.html
2. Run the .exe file and install
3. Set up JAVA_HOME environment variable as C:\Program Files\Java\jdk1.7.0_45
4. Set up PATH variable as ;$JAVA_HOME\bin
5. Verify Java installation in terminal/cmd using java -version.

<b>Tomcat 7 <b>

1. Apache Tomcat - http://tomcat.apache.org/
  Note: Always do a fresh install of Tomcat
  Note: Windows users should ensure that there are no spaces in the complete tomcat path as this causes errors with JSF tools in Sakai
  GOOD: C:\tomcat\, C:\SNAPP\installs\tomcat\
  BAD: C:\program files\tomcat\, C:\opt\apache tomcat 7.0.1\
2. Extract the files to C:\Tomcat 
3. Set environment variable: CATALINA_HOME=C:\Tomcat. Add $CATALINA_HOME\bin to PATH

<b>WAMP server<b>

1. Download the WAMP stack from http://www.wampserver.com/en/ . Run the .exe file
2. Run start Wampsever(wampmanager.exe)

Note: This step can be eliminated if you configure php in tomcat.

Steps to host SNAPP on server
-----------------------------

<b>SNAPP<b>

1. Download the SNAPP source available in github https://github.com/sandeepmjay/SNAPPSakai-Beta. 
2. Place this folder in the webapps folder of Tomcat.
3. Start Tomcat by running the C:\Tomcat\bin\startup.bat.
4. Open Firefox and enter the URL http://localhost:8080/SNAPP/index.html
5. Right click on SNAPP V2 Beta link and bookmark the link.


<b>File Saver<b>

1. Download the FileSaver project from github https://github.com/sandeepmjay/SNAPPSakai-Beta. 
2. Place it in C:\wamp\www\ folder.

After these steps you can share the bookmarklet link with faculty, students, researchers and they can just
deploy SNAPPSakai as a Bookmarklet


Deploying SNAPP on Forums
--------------------------
Currently works with latest version of Firefox.

1. SNAPP is a client-side bookmarklet application which can be deployed via the browser.
2. Login to your Sakai CLE(v2.8 & v2.9) instance. Choose a course with Forums.
3. Expand the Forum thread(View mode - by Conversation) for the forum to be analysed.
3. Run the SNAPP V2 Beta bookmarklet application on the expanded forum.
4. Accept the permissions to run the app and click on Run button.
5. Scroll to the end of the forum thread and you should see the SNAPP visualization embedded with in your forum page.







  
