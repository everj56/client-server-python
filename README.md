# client-server-python
## Required to use Python3
## Required libraries for server.py
1. import socket
2. import random
3. import sys
## Required libraries for server.py
1. import socket
2. import sys
## How to Run
1. Have two instances of your shell
2. Start the server in one shell with the following command and port number of choice:
   ```python
   python3 server.py <port>
   Example: python3 server.py 8008
3. Start the client in the other shell with the following command, the server machine hostname, and the port number of choice: 
   ```python
   python3 client.py hostname port number
   Example: python3 client.py 10.222.56.101 8008
