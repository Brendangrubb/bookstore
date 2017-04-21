# **Excelsior Books**
#### Brendan Grubb, 4/21/2017


&nbsp;
## Description
**Excelsior Books** is an application that demonstrates my ability to build a project using the Drupal framework. This website was built for the owner of a bookstore. The users of this site are able to access an about page and a page listing bookstore locations, plus a blogroll on the main page featuring news and updates. Authenticated users have access to exclusive content. Users designated "reviewers" are able to add book reviews which are viewable by everyone and displayed on a block through out the site. Reviewers can edit and delete their reviews. All users, regardless of role are able to contact the site administrator. 

&nbsp;
## Setup/Installation Requirements
##### _To view and use this application:_
* It is necessary to download and install a few programs to use this application
    * Go to [getcomposer.org](https://getcomposer.org/) to download Composer (a dependency manager) for free.
    * If you plan on using this app on a mac, go to [mamp.info](https://www.mamp.info/en/downloads/) to download MAMP for free. If you're not using a mac, make sure you have software installed that allows you to host a web server via Apache and manage a database via MySQL (WAMP, LAMP, etc)
* Go to the [Github repository](https://github.com/Brendangrubb/bookstore)
* Download the zip file via the green button
* Unzip the file and open the **_bookstore-master_** folder
* Inside of the **_bookstore-master/sites/db-backup_** folder, grab the **_bookstore.sql.zip_** file
* Open MAMP (or equivalent) and click on preferences.
    * In the Web Server tab, set the Document Root to the project folder, **_bookstore-master_**.
    * In the Ports tab, make sure that the Apache port number is set to 8888 and the MySQL port number is set to 8889
    * Click start servers.
* Type **_localhost:8888/phpmyadmin_** into your web browser
    * Click the _Import_ tab on the nav bar
    * Click _Choose File_ and navigate to **_bookstore.sql.zip_**
    * Click _GO_
    * Click the _User Accounts_ tab on the nav bar
    * Click _Add user account_
    * Enter _bookstore_ as username, _local_ as hostname and _bookstore_ as password
    * Check all _Global privilages_ and click _Go_
* Type **_localhost:8888_** into your web browser
* The application will load and be ready to use!

&nbsp;
## Known Bugs
* No known bugs

&nbsp;
## Technologies Used
* Drupal
* SQL
* HTML

&nbsp;
_If you have any questions or comments about this program, you can contact me at [brendangrubb@gmail.com](mailto:brendangrubb@gmail.com)._

Copyright (c) 2017 Brendan Grubb

This software is licensed under the GPL license
