# cs4530_final_project

1.Installation instructions and userguide, documenting the functionality of your system
 
Installation:
To run our program, we need to start it by entering the ‘npm run start’ command in terminal. After entering the command, the window of our program would pop up.  
 
User guide:
After you start the program, the login page would show up. Users can enter their username and password to login. And then they could see the login page of our program. Their username would be displayed on the right-top corner, and if they click it, they can go to the profile page or sign out.
 
It has two main functionalities. One is named ‘Single File Detector’, which can be used for comparing two single programs. If users are going to use ‘Normal Detector’, they could select their desired language on the top, and upload two files below that respectively. To start the comparison, users could click the white ‘Compare Structure’ button at the bottom. After that, portions of code, which are considered to be similar, will be highlighted respectively in two code display section. The blue ‘Compare Structure’ button is to generate a general report of the similarity, rather than highlighting them in their original section.
 
The other functionality is named ‘Multi File Detector’, which can be used for comparing two programs that have multiple files. Users could select the language, and upload two folders, rather than two files in the system. The following operations would be generally the same with ‘Normal Detector’
 
Functionality:
For the code of our system, we divide it into several components, such as ‘content’, ‘header’, ‘sider’, ‘select’, and ‘login’.
