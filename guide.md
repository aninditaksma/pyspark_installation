# pyspark_installation

This is a guide to install Pyspark in Windows system

Prerequsites (should have been installed):
- Java
- Python

1. Go to 
2. Select the Spark version and download the .tgz file
3. Install 7zip
4. Extract the .tgz with 7zip, then extract again the .tar file
5. Move the Spark folder to you root
6. Download winutils.exe on https://github.com/steveloughran/winutils/blob/master/hadoop-2.7.1/bin/winutils.exe
7. Go to system properties in your system, click the tab Advanced, then click Environment Variables on the bottom of the page.
8. Create new variable name "hadoop_home" with variable value to be the location of winutils, in my case is "C:\winutils", then click OK
9. Create another variable name "Spark_home" with the variable value to be the location of spark, in my case is "C:\spark", then click OK.
10. Add a new path "C:\spark\bin"
11. Open Command Prompt and type 'pip install pyspark'
12. And you're done!
