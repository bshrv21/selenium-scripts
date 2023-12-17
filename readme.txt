Versions Used:


Eclipse IDE: 2020-06 (4.16.0)
Java: JaveSE-1.8
Selenium-Java: 3.141.59
WebDriverManager: 5.5.3



Accessing Selenium on Projects:

1. Java Projects:

	When selected Java Projects, we need to create a Resources folder and copy the download Jar file of the Selenium. Then we need to add to the Build path to the projects.
		Under Resources right click on selenium jar file-> select Build path -> select Add Build path. This process will add the path under Referenced Libraries.

2. Maven Projects:
	
	When selected Maven Projects, we can directly add the depencencies code in the pom.ml file.
		Go to mvnrepository.com and search selenium-java -> select the more number of used -> copy the depencencies code -> paste in pom.xml file inside <dependencies>

Advantages of Maven project on Java Project:
	
	Maven projects has pom.xml file to take an advantage of handling the latest download for selenium-java jar file. Whenever there is a new build we can just update the version number in pom.xml file and save. But in Java projects we need manually download the jar file and follow the steps to build the path.


Download the WebDriverManager

	Go to mvnrepository.com and search webdrivermanager -> select the latest build -> copy the depencencies code -> paste in pom.xml file inside <dependencies>



Code to launch the Amazon website on Chrome -> select the 
