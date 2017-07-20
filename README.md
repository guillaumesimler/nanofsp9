# Linux Server

Authors
----
* the **setup of the Linux Server** was done by **Guillaume Simler**, a Udacity Frontend Nanodegree graduate and Full Stack Web Developer Student, more information and contact details on my [Github profile](https://github.com/guillaumesimler)

* the **application** was programmed by **GUillaume Simler***

Project description
----

The aim is to setup a Linux Server running an Apache webserver, a database (sqlite) and serving an WSGI app.

Of course the focus of the project is to allow a **secure usage** of the program


## a Word of caution !!!

The **Database** is **__not__** a postgrsql, but as a **SQLITE** as I made a longer break and the initial project was programmed with SQLITE.  




Ressources
----

The installated packages are:

* apache webserver using

> sudo apt-get apache2

* ws


Server IP Address & Ports:
----

The server is based on [Amazon Lightsail](https://amazonlightsail.com/) using the German Region - Frankfurt (eu-central-1). 

The IP Address is 

> 35.157.229.177


The __[uncomplicated Firewall](https://wiki.ubuntu.com/UncomplicatedFirewall)__ was setup and allows the access via the following three ports.

> SSH: **2200**
> HTTP: 80
> NTP: 123

**!!! SSH port is not standart !!!**

Additional user and extra key
----

The user **grader** was 
* created
* given sudo access

He/she can access the server using own SSH Keys stored on the [github repo](https://github.com/guillaumesimler/nanofsp9/tree/master/ssh)

* __grader__ is the private key
* __grader.pub__ is the public key
* __grader_putty.ppk__ is the private key prepare for the use with [Putty](http://www.putty.org/)

The connection **must occur on port __2200__** 


How to use
----


Repository
----
* the [working project](https://github.com/guillaumesimler/nanofsp9)
* the [initial project](https://github.com/guillaumesimler/nanofsp9)

License
----

The **current version** is under [_MIT License_](https://github.com/guillaumesimler/nanofsp9/blob/master/LICENSE.txt)