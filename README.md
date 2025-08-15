\# Task 8 – Java Maven Build in Jenkins



This repository contains a simple Java Maven project (`HelloWorld.java`) built using a Jenkins Freestyle job.



\## Steps I followed

1\. Created a Maven project with `HelloWorld.java` printing "Hello, Jenkins + Maven!".

2\. Added a `pom.xml` file with Maven compiler plugin configuration.

3\. Pushed the code to GitHub.

4\. Configured a Jenkins Freestyle job:

&nbsp;  - Source Code Management: Git with this repository URL

&nbsp;  - Branch: main

&nbsp;  - Build Step: Invoke top-level Maven targets → Goals: `clean package`

5\. Ran the job and verified \*\*BUILD SUCCESS\*\* in Console Output.



\## Build Success Screenshot

!\[Build Success](build-success.png)



