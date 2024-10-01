I recently worked on a Java application project where I implemented a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins.
Here’s a brief overview of what I achieved:

-->Technologies Used:
=============================
1. Jenkins: For automating the CI/CD pipeline
2. Java: For the sample application
3. Tomcat: For deploying the web application

Master-Slave Architecture: To distribute the workload efficiently

-->Project Highlights:
=========================
1. Set up Jenkins to automate the build, test, and deployment process.
2. Configured a master-slave architecture in Jenkins to ensure scalability and reliability.
3. Deployed the Java application to a Tomcat server seamlessly.
4. Achieved successful build and deployment results, ensuring the application is production-ready.

Tomcat Set-Up
=================
Goto Slave and install tomcat.(https://dlcdn.apache.org/)
Commands:
1. tar -zxvf apache-tomcat-9.0.74.tar.gz
2. cd apache-tomcat-9.0.74.tar.gz
3. vim webapps/manager/META-INF/context.xml ( Delete these 2 lines (21 and 22))
4. vim conf/tomcat-users.xml (Add these 3 lines at the end of the file)
5.  ./bin/startup.sh ( tomcat will get starts )


This project helped me deepen my understanding of CI/CD principles and the importance of automation in modern software development.

