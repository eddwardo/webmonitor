[![Build Status](https://travis-ci.org/eddwardo/webmonitor.svg?branch=master)](https://travis-ci.org/eddwardo/webmonitor)
webmonitor
==========

Simple webmonitor which gets page content and match for given string.

test running
------------

from project directory:

````````
tox
``````````


deploying
--------
Availible distros: Ubuntu (maybe Debian)
from project directory

on vagrant

````````
fab vagrant webmonitor
````````

on normal host

``````````
fab -H hostname webmonitor
``````````
