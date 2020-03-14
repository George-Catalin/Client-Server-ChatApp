# Client-Server-ChatApp
A Chat application is realized for the Client and the Server which is biased on Transmission Control Protocol (TCP) where TCP is the connection oriented protocol and is reliable. After starting a server on a specific port, users can establish a connection to it through a friendly Graphical User Interface mentioning the port and the IP address of the creator. The first user connected to the chat becomes the coordinator of that chat and is put in charge of maintaining the conversation and pinging the state of the group to all other members. On log out the title is lost and is inherited by other users.
# Summary
The program was made in Java NetBeans and it contains four important classes: Server, ServerGUI, Client and Client GUI <br/>
The Server class is the back end of the main server and it contains all the logic. <br/>
The ServerGUI class is the front end of the server and it contains a GUI for an easier management of the program. <br/>
The Client class is the back end of the main client and same as the Server class, it contains all the logic. <br/>
The ClientGUI class is the Graphical User Interface of the Client class and it is the main frame for the users to chat with each other. <br/>
<br/>
# Running the program
1. Opening the program in Java NetBeans <br/>
2. Running the Server class or the ServerGUI class (with GUI preferably). <br/>
3. Adding a desired port (the default is set to 1500). <br/>
4. Running the ClientGUI class. <br/>
5. Adding the IP address (if not, the default is set to localhost) and the Port number (default 1500). <br/>
6. Entering an ID (default is set to Anonymus). <br/>
7. Click log in and enjoy chatting. 

