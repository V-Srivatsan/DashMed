# DashMed

DashMed is a fully functional prototype of an application aimed at reducing the effort and time taken to order as well as deliver medicines. The working of the application can be understood using the flow chart below:

![DashMed-Flow](https://user-images.githubusercontent.com/63727128/182647843-59986cc8-3fba-4d64-9245-9c1d38106400.png)

## Usage
**Note:** This is a prototype, and needs some basic setup for all the components to work properly.

### Admin App
The apps can be sideloaded in any android phone running Android version 7.0 or higher.
After loading the DashMed-Admin app, use the following credentials to login:
`Username: gplex
Password: login0408`

In order to prevent unauthorised changes to this account, the password cannot be changed for this particular account.


### Ordering as a User
In order for your order to be picked up by a warehouse, it needs to have employees present, stocks in the inventory and be within a 5 km radius.
For this to work, you need to enable developer options and use the __Mock Location__ feature to emulate your location for this particular app. Select __DashMed__ and you're done!


##Update
Due to restrictions from heroku, the server has been taken down. The source code for the server and the other apps are given below https://github.com/V-Srivatsan/Dashmed-Server . The server itself is developed in Django and uses PostgreSQL. The extensions used in PostgreSQL are Postgis, HStore and PG_TRGM. 

User App: https://github.com/V-Srivatsan/DashMed-User
Warehouse Management App: https://github.com/V-Srivatsan/DashMed-Admin
Employee App: https://github.com/V-Srivatsan/DashMed-Employee
Server: https://github.com/V-Srivatsan/DashMed-Server
