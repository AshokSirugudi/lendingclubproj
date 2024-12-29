This is demo project, going through the functionality of Git & GitHub. Found an interesting and interactive website for GIT practice 
# https://learngitbranching.js.org/

Created a basic structure for the project. This project is more inclined towards Data engineering - Data cleaning, transformations and strategies. 

Project Structure : 
Folders:

1. CONF :  The CONF folder consists of the configuration information related to various enviroment like Development, Production, Testing. 
   a) spark.conf : Defines various enviroment for the project
   b) spark.app.name : Declares the app name in this example; spark.app.name = lendingclub
   c) spark.executor.cores : Declare the number of executor cores for the app.
   d) spark.executor.memory : Declare the executor memory for the app.
   
3. LIB : Files for LIB
   a) utils.py : This file is assigned to create spark sessions. 
   b) transformations.py : This file consists of all the applicable transformations. 
   
Files: 
1. main.py : This file acts as an entry point and takes care of all the function calls.
2. logger.py : This file handles logging. 

Above is the basic/minimum folders & files structure for the all the data engineering projects. In the GITHUB project itself we can verify the sample content of a simple configuration in files and folders. There might few additional files as results of testing and various GITHUB operations from local to remote repository and vice-versa. 
