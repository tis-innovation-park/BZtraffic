# BZtraffic

Traffic is a [free software](http://www.gnu.org/philosophy/free-sw.html) online application and is developed under AGPL License
* [Comune di Bolzano progetto intergreen](http://www.integreen-life.bz.it/) 
* [Tis Innovation Park](http://www.tis.bz.it) 
* ***web design*** [made in cima](www.madeincima.it) 
* ***developed by*** [Ethical Software](http://www.ethicalsoftware.it)

It helps the local travelers to choose the best passage thruogh Bolzano roads regarding to the traffic flow.


## Where to find documentation:
The documents of the API can be found on: http://ipchannels.integreen-life.bz.it/doc/
More technical info about hardware installation of the API can be found on: http://www.integreen-life.bz.it/approfondimenti-tecnologici

## How does Traffic work?
Traffic captures all the required datas from The Integreen API through the link: http://ipchannels.integreen-life.bz.it/LinkFrontEnd/
This link provides all necessary information to estimaste the traffic situation of streets in Bolzano. the API counts the vehicles, calculates the velocity and returns the datas.
With these datas from API, Traffic estimates the vehicular traffic of the streets and evaluates the time needed to travel with vehicle and bicycle from a place to another in Bolzano roads.

## Prerequisites
* ***JSON***
All the information retrieved from integreen API are in JSON format, so to begin with, it's necessary to have a base knowledge of what it is and how does it work. 
 more on [JSON](http://www.json.org)

* ***PHP***
In Traffic we acquire and manipulate the datas (comming from API) by a class and some functions which are written in PHP.
more on [PHP](http://www.php.net)

## Installation
* ***WEB SERVER***
Download and install a web server. Our recommendation is a package solution like XAMPP which contains a web server "APACHE", along with "PHP" and "MYSQL" [here](https://www.apachefriends.org/index.html) you can choose your compatible version to install.

* ***CODES***
Download the codes of the project on your local disk [here](https://github.com/tis-innovation-park/BZtraffic/archive/master.zip)
unzip the downloaded file into "htdocs" directory found in your XAMPP installation address.

ENJOY!



