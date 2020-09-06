NEET A MODULE INSTALLED?  
!pip install <package_foo>  
	!pip install tweepy  

A compilation of all basic Python 3 that is learned from Online tutorials and self learning through testing in projects.

There should not be any projects in here.


# Virtual Environment
1. Download Virtual Environment in root
	* ```pip install venv```
	
2. Make a new directory
	* ```mkdir [dir-name]```
	* ```cd [dir-name]```
	* ```$ python3 -m venv [name-of-new-virtual-environment]```

3. Activate new Virtual Environment
	* Unix ```$ source [name-of-new-virtual-environment]/bin/activate```
	* Windows ``` [name-of-new-virtual-environment]\Scripts\activate ```
	
# Tips
* List the Packages in the environment
	* pip list
* Check what kind of methods within package
	1. ```import [package-name]```
	2. ```dir([package-name])```
