# Unit IA: Client Project (Club Attendance Application)

# Criteria A: Planning

## Problem definition
The badminton club leaders have to mark attendance for all members every time they practice badminton. Currently, they use google sheets, which turn out to be very hard to use, especially when used in the gym with limited wifi. To streamline the process, the badminton club leaders have approached me to create an application that can efficiently record who's present and who's not. They want an application that has a GUI that has accessible buttons and textboxes to input attendance, and must work even without the internet. The client also wants a record of all the data inputted to check back later on. 

## Proposed Solution:

### Design Statement
I will design and make an application that will keep track of the list of students and their attendance for the badminton club leaders. The application will be able to keep track of all previous data (student list and attendance) through the use of a database and a login system. To ensure security and privacy, the login system will have a hashing system to secure everyone's password and will all be saved in a local database using SQLite. The application will have a GUI so that my client can easily guide themselves throughout the app. This all will be created using the Python 3.x language with the help of KivyMD for GUI construction. All code will be created and developed on the application, Pycharm. This app will take 4 weeks to complete and will be evaluated according to the criteria. 

### Why Python?
Contrast to every other programming language, I have chosen to use Python 3.x for numerous reasons. For starters, Python is the most well known and used programming language throughout the world, compared to the alternatives such as C++ and Javascript [1]. This will not only allow me to have greater access to resources and references but most importantly allow future developers to expand and update the application I have created, making it future proof. 
Personally as the developer, I am the most comfortable with programming in Python, meaning that not only will everything be streamlined and efficient but most importantly, the client will receive the application in a timely manner, without any extensions of the due date. Judging by the benefits of both the programmer and client, it's safe to say that Python is the right programming language to use for this project. 

### Why KivyMD?
KivyMD will be used to construct the graphical user interface (GUI) for the user to navigate throughout the app. Other alternatives such as Libavg or PyQT do exist when creating a GUI, however, unlike the other two, KivyMD is compatible with all 3 operating systems (including mobile devices) [2] making it easier for the client to access the application. Additionally, KivyMD’s goal, “to approximate Google's Material Design spec as close as possible without sacrificing ease of use or application performance.” [3] also greatly relates to the client's experience as the GUI is what the client actually sees and a good GUI is always appreciated in every application. KivyMD is also the library I am the most familiar with and will help me as a developer to not only finish on time, but also ensure a delivery to the client on time. For these reasons, I have come to the conclusion that KivyMD is the most appropriate GUI node for my project. 

### Why SQLite?
SQLite is a database engine written in the C language[4] but comes bundled with any Python interpreter such as pycharm without having to install any additional software [5]. Compared to other database applications, SQLite is cross compatible with a number of programs and operating systems [5] and is relatively simpler, shortening the time to develop a database. These factors will be beneficial to the client as the compatibility will ensure the client can access the database through the app from any platform they wish to use and also can be used to futureproof the application as future developers can modify the database if necessary. 
As the developer, I am the most familiar with this database structure and console which will allow me to create the database quickly and will ensure that the client's deadline is met. With this flexibility and superiority over other databases, I have decided to use SQLite for this project's database. 

## Success Criteria

1. The application must have a registration system where the user can register their email, username and password and are saved into a database.
2. The application must encrypt the users password in the local SQL database.
3. The application must record all data from name, attendnace status and date.
4. The application must 
5.
6.


## Client Approval

## Works Cited


# Criteria B: Design
## System Diagram

![](System_Diagram.jpg) 
