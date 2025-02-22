---
title: Advantages of Event-Driven Reference Architectures
description: Advantages of event-driven architectures, related to characteristics of pushing data.
---

# Push

Event-Driven applications use a broadcast style of communication when events occur. Rather than using a traditional request and response, in event-driven architectures a push-based communication is often used. Services no longer need to poll to receive updates, they need only subscribe to events and they will arrive as and when they are available (pushed). This can be powerful for on-the-fly data science workflows or real-time client dashboards.  

The following image shows the main differences in communication style between pull and push. 

![image](./images/push.png)
