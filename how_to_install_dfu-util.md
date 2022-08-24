# How to install dfu-util


### Windows:

1. Go to http://dfu-util.sourceforge.net/
2. Click on **releases**:
	- or go to http://dfu-util.sourceforge.net/releases/
2. Download the dfu-util binary files, i.e.,
	- dfu-util-0.11-binaries.tar.xz
	- download it to a folder e.g.,: **C:\dfu-util\\**
	- extract files
	- the Windows binaries are located in the **win64** folder.
3. Append the path of the **dfu-util.exe** to the system environment variable **Path**.
	- open environment variables
	- click on Path, then click Edit...
	- click 'New'
	- add 'C:\dfu-util\path\to\win64'
	- Save and Exit
4. Check that dfu-util is installed
	- open CMD and type:
	```
	dfu-util --version
	```
  	- if the terminal returns the version number dfu-util is successfully installed.  

### Linux:
```
 $ sudo apt-get install dfu-util
 ```
 
 -------------------------------------------------------------------------------------------
 
### NOTE: 
The version 0.11 of dfu-util (latest version as of 24/08/2022) is also available for download in this repository. See **dfu-util-0.11-binaries**

 

