# Module 10: Asynchronous Programming

> #### Novrizal Airsyahputra - 2206081780 - Advance Programming B

---

1. Original code of broadcast chat.

**ANS:**

![original](https://cdn.discordapp.com/attachments/1111642397248598067/1236066375617744966/image.png?ex=6636a804&is=66355684&hm=cc5e1d2c6fa4f65cc999ee7b47ee75291d00d44709f16709b5d284c01a6f6837&)

Based on the image above, I tried to run the server on Intellij IDEA & I opened 3 terminals to run the clients.
To run the server I used `cargo run --bin server` & to run the clients I used `cargo run --bin client`.
From the outputs, we can see that these 3 clients are connected to a single server.
When I tried to type a message in one of them, the other clients can see the input as well.
I personally think that this is so cool!

2. Modifying the websocket port.

**ANS:**

![modify](https://cdn.discordapp.com/attachments/1111642397248598067/1236071145212743871/image.png?ex=6636ac76&is=66355af6&hm=bf9a8a0597dc4ba9485a376a3f18ad075c9d252ed706d4d2dd70612f2ee9d14a&)

Based on the image above, I attempted to make a small change to the files `src/bin/client.rs` and `src/bin/server.rs` by changing the port to 8080. 
After the change, it turns out that all three clients and the server continue to run smoothly without any issues. 
This is because both the client and server are using the correct port, so there are no errors in the program.

3. Small changes. Add some information to client.

**ANS:**

![changes](https://cdn.discordapp.com/attachments/1111642397248598067/1236076910111621140/image.png?ex=6636b1d4&is=66356054&hm=317c48b99ff72fd6d2aefb42eb95ec2f45c01e9fab1e171a9e25c37a6fd380c4&)

Based on the image above, we can see that there is my computer's name which is LAPTOP-A4HG4HU7.
I tried to implement the `ghostname` dependency.
I modified the print statement in the `src/bin/client.rs` and `src/bin/client.rs` by adding the hostname.