**2.1. Original code of broadcast chat.**  
![](2.1.2.png)  
![](2.1.3.png)
![](2.1.4.png)
![](2.1.1.png)  

After we run the server with `cargo run --bin server` and run three clients with `cargo run --bin client` from different terminals, we can see that the server acts like, well, a server. It broadcasts the chats from a client to another client, so when a client types in a message in the command line, the server will transfer/send it to all clients connected to it.