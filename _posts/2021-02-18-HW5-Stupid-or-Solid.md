---
layout: post
title: "Stupid or Solid?"
---

I feel like I understand the generalities of SOLID (Single Responsibility Principle, Open/Closed Principle, Liskov Substitution Principle, Interface Segregation Principle, Dependency Inversion Principle) vs STUPID (Singleton, Tight Coupling, Untestability, Premature Optimization, Indescriptive Naming, Duplication) code, and see how some of these ideas are shaped from as early as a first or second programming class. We were told to use descriptive names (albeit often abbreviations) and told that if we were repeating the same code then it could probably be made a function instead. We were told that every class should be responsible for one thing and one thing only and told to test our code.

But at the same time, I find myself slightly confused by the specifics of some of these principles and terms, probably just because they are unfamiliar to me. But… should they be by the end of a 4-year computer science degree? While a computer science degree may be different from a software engineering degree depending on the institution, shouldn’t these principles apply to both industrial or academic code and be instilled from the early foundations either way?

The Singleton pattern and Tight Coupling are two concepts from STUPID code where I feel that I understand the general principle, but not necessarily the implementation or implications. Same with the Open/Closed Principle and Liskov Substitution Principle from the SOLID side. I feel like there was a good emphasis on these types of concepts in the first two or three programming classes, but these concepts weren’t explicitly focused on in the subsequent classes before this one. Maybe that’s not an issue and some people learned these things while proceeding through their courses, but surely I can’t be the only one that lacks the confidence to reliably follow SOLID principles while avoiding STUPID principles. 

Apart from lacking the confidence to reliably identify and/or implement these principles at this point in my career, I can see why they are generally good principles to follow. All of the principles center around the concept of making one code base more dynamic and robust rather than having to add superfluous code to handle something at a non-optimal point, which in turn results in repeating code or having to add more code to fix this. Based on some of the code from my open-source project this semester I actually was confused when first looking at the code base, but now I see how some of these principles came into play in the design and implementation of the app we are working on. Even though it doesn’t fully make sense to me because I’m not highly familiar with some of these principles, it’s made the code easier to navigate as I’ve become more familiar with it.

One thing that was interesting to me, especially after 230, 310, etc. was the two rules given to optimize an application: “don’t do it; (for experts only!) don’t do it yet”. Makes me wonder where exactly the line is between basic optimization and premature optimization as described here, and I honestly feel like part of the answer (on average) relates to human readability. 


