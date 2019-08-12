Friday Programming Test Project
Fifth Friday project to test our knowledge of functions, and other concepts v1.0.0 08.09.2019
By Anthony Golovin
Description/Specs
_spec: The program gives the user the ability to add stylists and manage clients while utilizing databases.


Setup/Installation Requirements
_1. Open the Terminal (Mac) or Git Bash (PC)
_2. Go to the dir. where you would like to install the file. (for ex. computer-name:~ Guest$ cd desktop
_3. To make a copy of a repository from Github on a local machine computer-name:desktop Guest$ git clone https://github.com/AnthonyGolovin/fridayproject4C.
_4. A boom a new file should appear named "fridayproject4C", enter the file through your terminal and then enter the HairSalon File. _
_5. (Now complete steps below in database set up before returning to this step) Then type dotnet run in the console, and copy the following address into your browsers URL "http://localhost:5000". _

EX: To create the database used by the web application, follow these steps:_

Setup/Installation Requirements (Database)
_1. Open a terminal and enter: mysql -uroot -pepicodus and a mysql environment should open up.
_2. Now we will create the database named anthony_golovin by entering CREATE DATABASE anthony_golovin. If you wanted to use another name, you would need to edit appsettings.json.
_3. USE anthony_golovin (to enter db)
_4. To create the first table stylists and it’s fields, please enter: 
CREATE TABLE `stylists` (
  `Name` varchar(255) DEFAULT NULL,
  `StylistId` int(11) NOT NULL AUTO_INCREMENT,
  PRIMARY KEY (`StylistId`)
);
_5. To create the table clients:
CREATE TABLE `clients` (
  `Name` varchar(255) DEFAULT NULL,
  `ClientId` int(11) NOT NULL AUTO_INCREMENT,
  `StylistId` int(11) NOT NULL,
  `Description` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`ClientId`)
);

None my code is for sure perfect, I checked.

Support and contact details
For any syntax errors please review the Setup/Installation Requirements section above and follow the above steps.

####Please insure you are in the correct directory in the terminal.

Feel free to get in contact with any questions, concerns, or if you want to make contributions to the code at: *AGOLOVIN97@live.com

Technologies Used
_*C#
_*MySQL Databases

License
Licensed under the MIT license

Copyright (c) 2016 _Anthony P Golovin_