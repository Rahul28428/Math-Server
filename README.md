# Math-Server
A simple client-server system allowing users to chat with a math server for mathematical operations.

In this project, we build a simple client-server system where you use the client to chat with a "math" server.

There are two types of client-server system created :

1) Single Process Server: In this server program, "server1" will be a single process server that can handle only one client at a time. If a second client tries to chat with the server while one client's session is already in progress, the second client's socket operations should see an error.
2) Multiprocess Server: In this server program, "server2" will be a multi-process or multi-threaded server that will fork a process for every new client it receives. Multiple clients should be able to chat simultaneously with the server.




To run any of the above two client-server programs follow these steps:

1) Open two separate terminal windows. One will be used to run the server, and the other will run the client.<br>
2) Using the cd command, navigate to the directory where your server.py and client.py files are located.<br>
3)Run the server: In one terminal window, run the server program by executing the following command: <br>
  python server.py            <br>
The server will start running and will be ready to accept client connections.<br>
4) Run the client: In the second terminal window, run the client program by executing the following command:<br>
  python client.py <br>
Your client program will connect to the server, and you can start sending requests to perform math operations.<br>
<br>
If you are using Python 3, you should use python3 instead of Python in the commands above. <br>
Example python3 server.py
