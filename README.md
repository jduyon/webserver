The simplest Python Webserver
=========

This script is the bare-minimum code required to get a simple web server up and running. 
It uses Python's HTTP built-in modules (BaseHTTPServer, SimpleHTTPServer) to serve an html page (labeled 'frontend.html' in this case).

How to use
=========

Download the zip (or run a git clone https://github.com/jduyon/webserver.git), and make sure you have Python 2.7 installed.
Run the webserver.py and your browser will automaticaly open up the 'frontend.html' page. 
This script is really good for quickly setting up a server to test your frontend's HTML / JavaScript / CSS.

Bugs
=========

-Don't expect any form of security with this
-The use case of this script is for showing how easily a webserver can be setup in python, and testing your frontend.
-Not packaged like a true python package, should be packaged (peter piper picked a pickled...)
