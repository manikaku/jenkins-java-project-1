I recently worked on a Java application project where I implemented a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins.
Here’s a brief overview of what I achieved:

-->Technologies Used:
=============================
-->Jenkins: For automating the CI/CD pipeline
-->Java: For the sample application
-->Tomcat: For deploying the web application
Master-Slave Architecture: To distribute the workload efficiently

-->Project Highlights:
=========================
Set up Jenkins to automate the build, test, and deployment process.
Configured a master-slave architecture in Jenkins to ensure scalability and reliability.
Deployed the Java application to a Tomcat server seamlessly.
Achieved successful build and deployment results, ensuring the application is production-ready.

Tomcat Set-Up
=================
--> Goto Slave and install tomcat.(https://dlcdn.apache.org/)
Commands:
--> tar -zxvf apache-tomcat-9.0.74.tar.gz
--> cd apache-tomcat-9.0.74.tar.gz
--> vim webapps/manager/META-INF/context.xml ( Delete these 2 lines (21 and 22))
--> vim conf/tomcat-users.xml (Add these 3 lines at the end of the file)
<role rolename="manager-gui"/>
<role rolename="manager-script"/>
<user username="tomcat" password="raham123" roles="manager-gui, manager-script"/>
--> ./bin/startup.sh ( tomcat will get starts )


This project helped me deepen my understanding of CI/CD principles and the importance of automation in modern software development.

