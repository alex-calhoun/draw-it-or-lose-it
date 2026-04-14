# draw-it-or-lose-it

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?:

The client for this project was The Gaming Room, a company that wanted to expand their game Draw It or Lose It. Their original version was only available as an Android app, and they wanted a web-based version that could work across multiple platforms and devices. The software needed to support multiple teams and players, make sure names stayed unique, and allow only one instance of the game service to exist in memory at one time. The design also needed to consider things like security, storage, memory management, and being able to support more users over time.

What did you do particularly well in developing this documentation?:

I think I did particularly well in clearly explaining the design choices and connecting them back to the client’s requirements. I made sure each section of the design document directly addressed what The Gaming Room needed, like supporting multiple users, keeping data consistent, and protecting user information. I also feel like I improved in explaining technical ideas in a way that would make sense to both the client and the development team.

What about the process of working through a design document did you find helpful when developing the code?:

Working through the design document was helpful because it let me plan out the structure of the software before focusing on the actual code. Breaking everything down into sections like requirements, design constraints, domain model, and recommendations made it easier to understand how all the parts of the application work together. This process helped me think ahead about things like memory use, security, and how the system would handle more users before getting into the coding side of it.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?:

If I could revise one part, I’d probably go back and improve the earlier domain model and system design explanations even more. I’d add more detail about how the classes relate to each other and maybe make the object-oriented principles a little clearer. Even though I improved this section throughout the course, I still think there’s always room to make the design explanation easier to understand.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?:

I interpreted the user’s needs by carefully looking at what The Gaming Room wanted the application to do and then designing the software around those needs. For example, because they needed support for multiple devices, I recommended a Linux-based web server environment and a distributed client-server system. Because they needed multiple teams and players, I designed the data structure and storage around that requirement.

It’s important to consider the user’s needs because the software should solve the client’s actual problem. If the design doesn’t match what the user needs, then even well-written code wouldn’t really be useful.

How did you approach designing software? What techniques or strategies would you use in the future?:

I approached designing the software by breaking down the requirements into smaller parts and then thinking about how each part would be supported by the system. I used strategies like analyzing constraints, identifying the relationships between objects, and comparing operating platforms before making a recommendation.

I’d continue using this step-by-step design approach because it helps organize ideas before development begins. I’d also continue using design documents, UML/domain models, and requirement analysis to plan similar applications.
