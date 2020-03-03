# Local Storage 

* Cookies can be used for local storage data of small amounts, but they have downsides like:

1- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

2- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

3- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

* HTML 5 Solved this by introducing HTML5 Storage

* HTML5 Storage is based on key/value pairs like objects, all data is saved as string and if you want to use any other type you have to convert like parseInt

* You can treat localStorage as ab associative array.

* You can also track changes to HTML5 storage area.

* Limitations in current browsers are: 5 megabytes each origin gets, quota exceeded error if you exceed this 5 mb, and no if you want to ask user for more storage space.

* SQL is the next step, its a web database that you can save data to, and includes statements like select, update , insert.


