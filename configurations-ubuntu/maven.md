### Installing Maven
Run the following command in the terminal
- sudo apt-get install maven


Edit the environment variables. Open the file “environment” with the gedit. In the terminal:
- sudo gedit /etc/environment

Add the following lines in the end of the file:
- M2_HOME="/usr/share/maven"
- M2="/usr/share/maven/bin"


Check if your Maven is configured now. In the terminal:
- mvn
