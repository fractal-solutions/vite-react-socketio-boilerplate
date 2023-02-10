
VITE-REACT + SOCKET.IO BOILERPLATE
========================================
# *by Quassa*

Implemented basic socket.io functionality with a Vite-React front-end, a nodejs back-end that leaves room for whatever implementation.
Allows sending of messages back and forth between the server and client to allow you to implement server side techniques,
offering protection of data, all while allowing for lightweight Vite-React modern front-end framework.


HOW TO START 
=======================================
Download and Extract RAR file. 

with terminal in the server directory:
**npm start**

with terminal in the client directory:
**npm run dev**

NOTE: **you might want to change the IP address/ Port used depending on your setup.



BUILD FROM SCRATCH
==================
From empty Client + Server document structure:
==============================================
Server Commands:

**npm init -y**

**npm install express cors nodemon socket.io** 

Client Commands:

**npm create vite@latest**

**npm install socket.io-client react-router-dom**
