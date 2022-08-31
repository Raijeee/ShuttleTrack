# Unit IA: Client Project (Club Attendance Application)

# Criteria A: Planning

## Problem definition
The badminton club leaders have to mark attendance for all members every time they practice badminton. Currently, they use google sheets, which turn out to be very hard to use, especially when used in the gym with limited wifi. To streamline the process, the badminton club leaders have approached me to create an application that can efficiently record the attendance of the club. They want an application that has a GUI that has accessible buttons and textboxes to record attendance with individual names and must work even without access to the internet. 

## Proposed Solution:

### Design Statement
I will design and make an application that will keep track of the list of students and their attendance for the badminton club leaders. The application will be able to keep track of all data through the use of a database and a login system. To ensure security and privacy, the login system will have a hashing system to secure everyone's password and will all be saved in a local database using SQLite. The application will feature a GUI so that my client can easily guide themselves throughout the app. This all will be created using the Python 3.x language with the help of KivyMD for GUI construction. All code will be created and developed on the application, Pycharm. This app will take 4 weeks to complete and will be evaluated according to the criteria.

### Why Python?
Python is ranked first in the “most well known and used programming language” [1] throughout the world, compared to other alternatives such as C++ and Javascript. This will not only allow me to have greater access to resources but most importantly allow future developers to update the application I have created, future proofing it. As the developer, I am most knowledgeable in programming Python, meaning that the coding process will be shorter, ensuring that the client will be able to receive the application before the deadline. Considering the benefits of the client and contrast to other alternatives, it's safe to say that Python is the most suitable programming language. 


### Why KivyMD?
Alternatives such as Libavg or PyQT do exist when creating a GUI, however, unlike the other two, KivyMD is compatible with all 3 operating systems (including mobile devices) [2] making it easier for the client to access the application. Additionally, KivyMD’s goal, “to approximate Google's Material Design spec as close as possible” [3] also greatly relates to the client's experience as the GUI is the front end of the application and is what the client sees. KivyMD is also the library I am the most familiar with and will help me as a developer to not only finish on time, but also ensure a delivery to the client on time. For these reasons, I have concluded that KivyMD is the most appropriate GUI library for my project.

### Why SQLite?
Compared to other databases such as Improvado or Oracle RDBMS, SQLite is cross compatible with a number of programs and operating systems [4]. These factors will be beneficial to the client as the compatibility will ensure the client can access the database through the app from any platform they wish to use and also can ensure futureproofing of the application as future developers can modify the database if necessary. As the developer, I am the most familiar with this database structure which will allow me to create the database quickly and will ensure that the client's deadline is met. With this flexibility and superiority over other alternatives, I have decided to use SQLite for this project's database.

## Success Criteria

1. The application must have a registration system where the user can register their email, username and password and are saved into a database.
2. The application must encrypt the users password in the local SQL database.
3. The application must record all data from name, attendnace status and date.
4. The application must work even without access to the internet.
5. The application must have a home screen that has an option to log attendance data, view past data or logout.
6.


## Client Approval

## Works Cited


# Criteria B: Design
## System Diagram

![](System_Diagram.jpg) 
