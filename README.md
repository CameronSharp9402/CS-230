# CS-230 Operating Platforms

# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
A company called Gaming Room sought to develop a multi-platform networked version of their popular mobile game "Draw It or Lose It" that would allow several players to join to shared game rooms through a centralized server. The creation of a client-server system that could handle player connections, operate numerous game rooms concurrently, and preserve the state of each game was one of the client's software needs. The client program has to provide real-time game participation, communication through a basic chat function, and the creation or joining of rooms. In order for players on Windows, macOS, and Linux to be able to participate, the system needed to be cross-platform compatible. Additionally, the server needed to be able to support multiple users at once while maintaining safe and reliable connection.

# What did you do particularly well in developing this documentation?
Creating the documentation for the system design was one area in which I believe I really shined. I carefully considered the advantages and disadvantages of Linux, Windows Server, and macOS Server when conducting extensive study and comparing several operating system options for the server. In order to make sure the specifications were practical and scalable, I also defined the hardware requirements for the client and server. It was simple to provide a clear, expert justification for my recommendations because of this attention to detail.

# What about the process of working through a design document did you find helpful when developing the code?
Thinking about the actual code implementation was made much easier after working through the design paper process. I was able to divide the project into smaller, more manageable parts by taking the time to thoroughly comprehend the system requirements and architecture before writing any code. These included the client-side connection handling, the server's room management features, and even some initial ideas regarding message passing protocols. I already had a roadmap to follow thanks to this methodical approach, which made the actual coding lot less daunting.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part of the documentation, I would improve the section discussing security measures. While I mentioned encryption and authentication, I think I could have gone further by outlining specific protocols (like TLS 1.3), and perhaps even including a sample authentication flow to demonstrate how users could securely join a game. Including this extra level of detail would have made the documentation stronger and more actionable for future developers who might work on the project.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I kept going back to the client's explanation of the game and its objectives to make sure I was correctly grasping the user's needs. This was crucial since creating a system that satisfies user vision while taking technical viability into account is essential to the design's success. For instance, even though UDP might have been faster, the client's emphasis on the value of a seamless player experience led me to suggest TCP over UDP for dependable data transport. When converting user requirements into design choices, striking a balance between technical feasibility and user expectations is crucial.

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
When approaching software design, I relied heavily on techniques like requirements gathering, system decomposition, and architecture diagrams to map out the client-server interactions. In the future, I would further enhance my process by creating sequence diagrams to fully visualize the flow of data between components and perhaps even incorporating user stories to ensure the design stays closely aligned with the user experience. Taking these extra steps would help make future projects even smoother, particularly when working on distributed systems like this one.
