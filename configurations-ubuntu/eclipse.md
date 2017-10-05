# Eclipse 
Download eclipse installer from http://www.eclipse.org/ and run the installer.

# Configuring the launcher:
Create a file eclipse.desktop under .local/share/applications/
- In the terminal run: gedit .local/share/applications/eclipse.desktop 
- Insert the following content:

```sh
[Desktop Entry]
Name=Eclipse
Type=Application
Exec=/home/USERNAME/eclipse/java-mars/eclipse/eclipse
Terminal=false
Icon=/home/USERNAME/eclipse/java-mars/eclipse/icon.xpm
Comment=Integrated Development Environment
NoDisplay=false
Categories=Development;IDE;
Name[en]=Eclipse
```
