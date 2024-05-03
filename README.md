# Module 10: Asynchronous Programming

> #### Novrizal Airsyahputra - 2206081780 - Advance Programming B

---

1.Original code of broadcast chat.

**ANS:**

![original](https://cdn.discordapp.com/attachments/1111642397248598067/1236066375617744966/image.png?ex=6636a804&is=66355684&hm=cc5e1d2c6fa4f65cc999ee7b47ee75291d00d44709f16709b5d284c01a6f6837&)

Based on the image above, i tried to run the server on Intellij IDEA & i opened 3 terminals to run the clients.
To run the server i used `cargo run --bin server` & to run the clients i used `cargo run --bin client`.
From the outputs, we can see that these 3 clients are connected to a single server.
When i tried to type a message in one of them, the other clients can see the input as well.
I personally think that this is so cool!