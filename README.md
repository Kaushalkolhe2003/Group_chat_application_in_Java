# Group_chat_application_in_Java

Project Description:
This Java project demonstrates a simple multicast group chat application using MulticastSocket, allowing users to engage in real-time group discussions over a network. The application enables participants to send and receive messages within a multicast group.

Key Features:

Users can specify the multicast host and port number as command-line arguments.
Participants enter their names to identify themselves in the chat.
Messages are sent to the multicast group and received by all participants.
The application supports graceful termination with the "Exit" command.
It uses multithreading to handle message reception and user input concurrently.
Usage:

Run the program with two command-line arguments: the multicast host address and the port number.
Enter your name to join the chat.
Start typing messages, and they will be broadcast to all participants in the multicast group.
To exit the chat, simply type "Exit."
