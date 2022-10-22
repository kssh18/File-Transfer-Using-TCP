# TCP-File-Transfer

This is a Java application that :

- built using Java Socket Programming.

- uses TCP for file transfer.
	
- has a Graphical user interface (GUI) built using Java AWT and Java Swing.
	
- Uses multithreading to allow multiple users to connect to a server at once.
	
- mandates the server to specify a working directory as a command line argument with the freedom to specify a custom port number as the second argument. (The default port number has been set to 3333)
	
- server assigns connection IDs to the clients connected.
	
- mandates the client to specify a working directory as a command line argument. It allows the user to specify the host address and if not specified, defaults it to Localhost. In this case, the user can also specify the port number as the third argument.
	
- Displays files and directories present in the server working directory and allows the client to select files and download them onto the client system.
	
- Allows the client to upload files to the server working directory. This allows 2 clients to transfer files through he server.
	
- You may call it ShareIt, Xender or something similar for laptops and PCs :wink: 
	

## Getting Started
```
git clone https://github.com/mansimarkaur/TCP-file-transfer
cd TCP-file-transfer
```
For *server* :
```
javac TCPServer.java
java TCPServer <server directory name>
```

For *client* :
```
javac TCPClient.java
java TCPClient <client directory name> 
```
Enter file name and click on **upload**. :arrow_up:

Choose file to be downloaded from the panel and click on **download**. :arrow_down:

**Server and Client can interact only through the same port number**

## Prerequisites

If you do not have Java installed, refer to this [Java installation guide](https://www.java.com/en/download/help/download_options.xml)

*For newbies, remember to set path variables in Windows and OSX*

### Contributors
[![portfolio](https://img.shields.io/badge/Likhit_Kalla-E23?style=for-the-badge)](https://github.com/likhitkalla)<br>
[![portfolio](https://img.shields.io/badge/Koganti_Sri_Sai_Harshith-072F5F?style=for-the-badge)](https://github.com/kssh18)<br>
[![portfolio](https://img.shields.io/badge/Yashwanth_Kiran-1e90ff?style=for-the-badge)](https://github.com/iyashk)<br>

