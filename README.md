# Chat-Application---John-Bryce-Training

Chat application between registered users using OOP development &amp; .NET framework infrastructure in C#.
This Chat project is assignment from Programming the .NET Framework 4.0/4.5 with C# 5.0 course in John Bryce Training.

You can read about this course here: http://johnbryce.com/syllbus/Develope/70240.pdf

### How will the app work?
The system will have an application that will be installed by a user who wants to chat with other users on the network.
This application is called "client side." With the client application, users can send and receive messages from other chat participants.
 
### How does the client-side app communicate with other computers? (Sends and receives messages)
The client side app can not tell which other users are on the network (what their IP address) is participating in the chat.
When we want to send a message to all participants, instead of sending the message to all the participants (we do not know who is connected to chat at any time), 
it would be wise if we save a message Hotline to which we send the message and distribute our message to the other participants.
The Hotline should know at any given time who is currently connected to chat. This is where the server-side app comes in.

### How will the "Server-Side" app work?
Write another application (server side) that will be the message center.
Each chat user must connect to and communicate with the server.
That is, we will send our messages to the server, which will distribute them to all other participants, and we will receive back the messages that other participants have sent to us.

### Feedback
![alt text](https://github.com/Dvir570/Chat-Application---John-Bryce-Training/blob/master/Feedback%20on%20the%20project.jpeg)
