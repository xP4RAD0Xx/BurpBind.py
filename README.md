# BurpBind.py
- Custom burp extension using the Burp API to allow user to connect to bind shells.
- It makes use of socket to connect to the server along with threading to allow for sending and recieving at the same time.
- Since it is a burp extension it requires configuring Jython in BurpSuite Extentions settings and makes use of the Burp API.
- Dependecies: burp, javax, sys, time, socket, threading
