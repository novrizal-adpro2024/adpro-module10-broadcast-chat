# Module 10: Asynchronous Programming

> #### Novrizal Airsyahputra - 2206081780 - Advance Programming B

---

1. Original code of broadcast chat.

**ANS:**

![original](https://cdn.discordapp.com/attachments/1111642397248598067/1236066375617744966/image.png?ex=6636a804&is=66355684&hm=cc5e1d2c6fa4f65cc999ee7b47ee75291d00d44709f16709b5d284c01a6f6837&)

Based on the image above, i tried to run the server on Intellij IDEA & i opened 3 terminals to run the clients.
To run the server i used `cargo run --bin server` & to run the clients i used `cargo run --bin client`.
From the outputs, we can see that these 3 clients are connected to a single server.
When i tried to type a message in one of them, the other clients can see the input as well.
I personally think that this is so cool!

2. Modifying the websocket port.

**ANS:**

![modify](https://cdn.discordapp.com/attachments/1111642397248598067/1236071145212743871/image.png?ex=6636ac76&is=66355af6&hm=bf9a8a0597dc4ba9485a376a3f18ad075c9d252ed706d4d2dd70612f2ee9d14a&)

I attempted to make a small change to the files `src/bin/client.rs` and `src/bin/server.rs` by changing the port to 8080. 
After the change, it turns out that all three clients and the server continue to run smoothly without any issues. 
This is because both the client and server are using the correct port, so there are no errors in the program.