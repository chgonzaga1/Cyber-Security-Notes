File Transfer Protocol(FTP)

This protocol is developedd for transfering files between the network. 
By default, it listens to 

We can use ftp on the command line then type ip address 

ex) ftp 172.16.241.13

From here on, it automatically requests for a username to login to

You also type RETR todownload a file from the server to a client
STOR is also used to upload a file from the client to the the server.

FTP usually supports two types of transfer.
TYPE A - ASCII and Type I - Binary Mode

Type ASCII Mode:
Fixes formatting for text so it can be readible.

Binary Mode:
Transfers raw bytes with no modification. Usually used for anything
that should not changed

the get command from FTP is used to download files
