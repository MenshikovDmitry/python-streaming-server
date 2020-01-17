# python-streaming-server
Use only one connection from camera to serve multiple viewers.  
Forked from https://github.com/golubaca/python-streaming-server  
## Usage:  
server:
```bash
~$ python Main.py
```  

client:
```bash
~$ python client/recv.py <IP_ADDRESS> <CAMERA_STRING>
```  
To test locally with default USB camera:
```bash
~$ python client/recv.py 127.0.0.1 0
```
