# Installing Java
Add the required repository ppa:webupd8team/java and run the installer. In the terminal:
- sudo apt-add-repository ppa:webupd8team/java
- sudo apt-get update
- sudo apt-get install oracle-java8-installer (In this step, the license agreement will be prompted. Select “ok” and then “yes” to proceed!)

Edit the environment variables. Open the file “environment” with the gedit. In the terminal:
- sudo gedit /etc/environment

Add the following line in the end of the file:
- JAVA_HOME="/usr/lib/jvm/java-8-oracle"

Check if your java and java compiler is configured now. In the terminal:
- java
- javac
