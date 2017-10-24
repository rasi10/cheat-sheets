### apt-get (on Ubuntu!)
**_Installing a package_**
```
sudo apt-get install package  (e.g. jmeter)
```
|Parameter |Description|
|-----|-----|
|-h | help|
|-d | Downloads the packages, but do not install them|
|-f | Fixes errors on the installation |
|-s | Simulates the operation, but do not do it for real|
|-y | Answers "yes" to all the questions [Y/n]|
|-u | Shows packages that will also be updated|

**_Removing a package (without deleting the installation packages)_**
```
sudo apt-get remove package (e.g. jmeter)
```

**_Removing a package (deleting the installation packages)_**
```
apt-get --purge remove package (e.g. jmeter)
```

**_updating packages (deleting the installation packages)_**
```
apt-get -u upgrade
```
