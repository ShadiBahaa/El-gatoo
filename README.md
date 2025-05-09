# El gatoo

## Description:

### It is a multi-user chatting app that simulates the main Whatsapp functionalities:

 1- Signing in/up
 
 2- Adding contacts
 
 3- Chatting with different users on different machines
 
### The architecture of the app is built on the following CS concepts:

 1- Graphical User Interface using Swing (For creating the visual (front end) part of the app)
 
 2- Object Oriented Programming (For creating different objects that resemble the entities of the system)
 
 3- Design patterns and SOLID principles (For designing maintainable, reusable, and extensible classes)
 
 4- Database system (For handling accounts information and saving chat history)
 
 5- Networking (For communicating between two contacts on different devices/ same device/ online server hosting)
 
### Tools, Technologies and CS conecpts:

 Java - Swing - MySQL - Gradle - OOP - Design patterns - Xampp - NetBeans
 
## Testing:

### For testing the project functionalities on the same device, it is highly recommended to follow this guideline:

 1-	Download the code folder
 
 2-	Download Netbeans from https://netbeans.apache.org/ and setup it
 
 3-	Download JDK 18 from https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html and setup it
 
 4-	Download Xaamp from https://www.apachefriends.org/download.html and setup it
 
 5-	Go to installation folder of Netbeans, -> etc folder -> netbeans.conf and change netbeans_jdkhome to the path of JDK 18
 
 6-	Open netbeans, then open file menu -> open project, choose the path of downloaded folder
 
 7-	If there are some issues to be resolved appear at starting, click resolve
 
 8-	In the project panel, open IDatabaseInfo from BackEnd package
 
 9-	Change the url to: "jdbc:mysql://localhost:3306/chat",  user to: “root” and password to: “”
 
 10-	Run the xaamp server as an administrator
 
 11-	Click start button besides apache and Mysql services
 
 12-	Click admin besides apache to open the localhost website
 
 13-	From above, choose phpMyAdmin, go to Databases and create the database named by “chat”
 
 14-	Choose chat database from the left panel, then import, and finally upload chat.sql file attached 
 
 15-	Go to Netbeans IDE, build the application, and run it
 
 16-	Open the project folder -> app folder -> build folder -> libs folder and you will find the jar file of the program
 
 17-	Open two different applications and enjoy!
 
### For some connection issues that are related to xaamp sever, it is highly recommended to do this (this is a try-and-error approach and maybe there are better solutions):

 1-	Changing the port number of Mysql service, by selecting config in the control panel of xaamp and choosing my.ini. inside the file update the port number (mostly 4306 works).
 
 2-	Creating a new user and password on the phpMyAdmin page, by selecting users accounts form above and creating a new user
 
 3-	Now you can replace 3306 in the url by 4306, and change the user and password to the new ones.
 
## Screenshots:

![Add Contact](https://user-images.githubusercontent.com/33010011/209451413-3ee3b424-362b-42c1-9e44-2d43457a0ad9.png)
![Other User Info](https://user-images.githubusercontent.com/33010011/209451415-cc8c749d-0b1a-4f10-845c-d7f8db81d663.png)
![Sample Chat 1](https://user-images.githubusercontent.com/33010011/209451421-19e51921-dcc6-4527-a66b-c50704f9fdfe.png)
![Sample Chat 2](https://user-images.githubusercontent.com/33010011/209451427-9d112d1d-fa96-4a10-a8e8-fe98e18f2488.png)
![SignIn page](https://user-images.githubusercontent.com/33010011/209451431-b03c2099-061f-46e8-84ad-f8d52deb2609.png)
![SignUp page](https://user-images.githubusercontent.com/33010011/209451435-6378d512-5567-43e0-9bb7-e6cf97b4a081.png)
![User Info](https://user-images.githubusercontent.com/33010011/209451437-54fac24d-cca9-4f9e-9b75-8773e638742b.png)
![User Interface](https://user-images.githubusercontent.com/33010011/209451443-a34f341d-585f-4829-9716-1536c88be471.png)







