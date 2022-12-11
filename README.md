# CHATROOM APPLICATION

A chatroom built in C++ using the concepts of socket programming and multi-threading. It supports chatting among multiple clients.
By using socket programming on AWS platform, Interaction between admin and client can be effectively carried out, means the clients can chat with the admin or can discuss any query.


# HOW TO RUN 
1. Clone this repository
2. Run the following commands in your teminal:
   g++ server.cpp -lpthread -o server
   g++ client.cpp -lpthread -o client
3.To run the server application, use this command in the terminal :
  ./server
4. Now, open another terminal and use this command to run the client application :
  ./client
5. For opening multiple client applications, repeat step 4.
