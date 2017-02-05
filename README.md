# BasicFTPServerUsingSocketProgramming-
The File Transfer Protocol (FTP) is a standard network protocol used to
transfer computer files between a client and server on a computer network.
FTP is built on a client-server model architecture and uses separate control and
data connections between the client and the server. FTP users may authenticate
themselves with a sign-in protocol, normally in the form of a username and
password, but can connect anonymously if the server is configured to allow it.
#Serverclass
Server class provides the application for the remote machine to connect to the
client machine. The server class opens the connection on port 4000 and listens
for a client socket. Once the client socket is opened, the server connects to the
client socket. Now, data can be easily transferred between the server class and
client class.
It takes the data whether to upload or download and proceeds to perform the
correspondent task.
#Clientclass
Client class is the application on client’s system. The client has to login using
username and password set up by the server administrator. The client has to
provide the ip address of the server s/he wants to connect to. If the client is
authenticated, a connection is set up. The client socket will open and send
information to the given ip address. If the server socket which is listening accepts
the socket, a connection is set up. Depending on whether the user wants to
upload or download, required operations will be taken up.
