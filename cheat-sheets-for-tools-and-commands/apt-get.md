## Package management with apt (On Ubuntu)


**_Help manual for apt-get _**
```
man apt-get
```

## Parameters
**_Parameters to use with apt-get_**
|Parameter |Description|
|-----|-----|
|-h | help|
|-d | Downloads the packages, but do not install them|
|-f | Fixes errors on the installation |
|-s | Simulates the operation, but do not do it for real|
|-y | Answers "yes" to all the questions [Y/n]|
|-u | Shows packages that will also be updated|


## Installing packages
**_Installing a package_**
```
sudo apt-get install <package_name>   (e.g. jmeter)
```

**_Installing multiple packages_**
```
sudo apt-get install <package1_name> <package2_name> <package3_name>
```

**_Installing a package and building the dependencies_**
```
sudo apt-get build-dep <package_name>  (e.g. jmeter)
```


## Removing packages
**_Removing a package (without deleting the installation packages)_**
```
sudo apt-get remove <package_name>  (e.g. jmeter)
```

**_Removing a package (deleting the installation packages)_**
```
apt-get --purge remove <package_name>  (e.g. jmeter)
```

**_Removing packages that were installed by other packages that are not longer needed_**
```
sudo apt-get autoremove <package_name>
```


## Maintenance commands
**_Reloading the /etc/apt/sources.list or /etc/apt/preference, after a change_**
```
sudo apt-get update
```

**_Upgrading all installed packages_**
```
sudo apt-get upgrade
```

**_Diagnostic tool_**
```
apt-get check
```

**_Removing .deb files that are not longer installed on your system_**
```
sudo apt-get autoclean 
```
**_Removing all packages from the package cache_**
```
sudo apt-get clean
```


## Searching commands
**_Listing packages whose names or descriptions contains <search_term>_**
```
sudo apt-cache search <search_term>
```

**_Listing the packages and showing if the package is already installed on your system_**
```
sudo dpkg -l *<search_term>*
```

**_Listing files in packages_**
```
sudo dpkg -c foo.deb
```

**_Showing which packages owns <package_name>_**
```
dpkg -S <filename_search_pattern>
```

**_Shows which packages provides a file_**
```
sudo apt-file search <filename_search_pattern>
```

**_showing all packages in the system_**
```
sudo apt-cache pkgnames
```

**_Search for file that contains <filename> as whole word _**
```
sudo apt-cache search <filename> | grep -w <filename>
```



**_Lists for a particular executable_**
```
sudo dpkg -L package | grep /usr/bin 
```
