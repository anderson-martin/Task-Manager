# Task-Manager

## What is it?
Task-Manager enables companies to assign tasks to their employees and manage their activities. 
Me and my classmates did this as part of our school project. For designing this application, we analyzed organizational structure of S-market (in Finland), and this application is an efficient solution for their communicational problem. However, this app can be used for any other big organization too. 

###### This image depicts our solution idea. Groups can manage and be managed. Each user can belong to multiple groups. HR has the authority to define the authority levels.
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/eight.jpg)

## What's special about it?

It's highly scalable! You can create unlimited number of hieracrhy levels (=group) in your organization, each having customized authority and communicates effectively with it's supperior and lower level groups. While you recieve tasks from your higher level groups, you can assign tasks to your lower levels. Also, in case of any problem, you can file an issue and send to your managers.

###### This image depcts a typical application case: different level of hierarchies branching from top level management. There is no limit for number of hierachies!
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/nine.jpg)


## Architecture

###### There are two separate servers. Node Express Server serves static files (JS, CSS files), runs Frontend stack (Redux) and procies the API requests to the API server (Java EE)
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/ten.jpg)

## How does it look like?

###### Login page including some introductions
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/one.png)


###### Task View enables the user to see all the tasks that he/she has recieved/assigned. 
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/two.jpg)


###### Following figure illustrates how user can create a new task (for the groups under his control) and assign a deadline & description to it.
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/three.jpg)


###### Only HR users have the previliege of creating user groups and defining authority relationship between them.
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/four.jpg)


###### HR can add/remove users to groups
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/five.jpg)


###### For each group, HR has to define which subgroups they can assign tasks to, and from which superior groups they can recieve tasks.
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/six.jpg)


###### HR has access and can change details of each user
![alt tag](https://github.com/anderson-martin/Task-Manager/blob/master/pictures/seven.jpg)


## Technology stack & codes
### Backend
JAX-RS, Jersey 2.25.1, JPA, Hibernate 5.2.7, Junit 5, Maven, Glassfish Server

### Frontend
React, Redux, Jest, Express Mock API, Express Production Server

You can find Frontend and backend codes in following repositories:
(Following repos are backups that I got from our common repos)

[Back-end repository](https://github.com/anderson-martin/TaskManager-Backend)

[Front-end repository](https://github.com/anderson-martin/TaskManager-FrontEnd)










