# bicycle_online_store

This project is an online store which has two main parts, including:
- customer part where customer can view bicycles and its details as shown below:
<img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_bicycles_user.png" alt="drawing" width="400"/>
- second part involve admin area where an admin have to login, and they can do (CRUD operations via website), as shown below:
<img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_bicycles_admin.png" alt="drawing" width="400"/>
Furthermore, the admin can also add, edit or delete (CRUD) other admins:
<img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/view_admins.png" alt="drawing" width="400"/>

## Steps to run the program
1. Download the WAMP server on you local machine from [here](https://sourceforge.net/projects/wampserver/), and install it, then click on the icon to run it
2. Open the directory folder by clicking on the <i>www directory</i>, as shown on the image below:
<img src="https://github.com/AjayaRai/bicycle_online_store/blob/main/images/mySql_console.png" alt="drawing" width="400
4. On the folder, git clone this repo
5. THen from the image shown above, click on the <i>MySQL console</i>
6. On the MySQL console, type <i>GRANT ALL PRIVILEGES ON chain_gang.*TO 'webuser'@'localhost' IDENTIFIED BY '123456';</i>
7. Create a DB via MySQL console, by typing "CREATE DATABASE chain_gang;"
8. Then, type "USE chain_gang;"
9. Copy the [chain_gang.sql](https://github.com/AjayaRai/bicycle_online_store/blob/main/chain_gang/chain_gang.sql) content, and paste it to the console
10. Finally, go to the [here](http://localhost/chain_gang/public/) to see the client page OR click [here](http://localhost/chain_gang/public/staff/) to view the admin page where you have to login as userName: raiaj123, password: Password£1234
