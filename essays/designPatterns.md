---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-03-27
published: true
labels:
  - Software Engineering
  - Learning
---

<img width="300px" class="float-start pe-3" src="../img/ICS314/smartQ.png">

## Design Patterns
Design patterns are reusable solutions to common problems encountered in software design and development. They offer structured approaches to solving these problems by encapsulating best practices and proven solutions within specific contexts. Serving as templates or blueprints, design patterns guide developers in crafting software architectures that are flexible, maintainable, and scalable. By abstracting common design challenges into reusable components, these patterns enhance communication among developers, promote code readability, and accelerate the development process through well-established solutions to recurring issues.
## Design Patterns in Clubs At Manoa Project
In our Clubs At Manoa project, we implement the Singleton design pattern through our MongoDB collections. Collections such as Clubs, Profiles, and Interests are instantiated once and reused across the application, typical of the Singleton pattern in JavaScript. For instance, the Clubs collection is defined once with the line export const Clubs = new Mongo.Collection('clubs'); in a dedicated module. This ensures the collection is created only once and is available throughout the application by imports. This single instance use across various parts of our system ensures data consistency and integrity, preventing discrepancies and centralizing the management of the collection’s schema and operations. This practical application of the Singleton pattern enables streamlined data handling and operations within Clubs At Manoa, illustrating how design patterns can significantly enhance software development practices.
