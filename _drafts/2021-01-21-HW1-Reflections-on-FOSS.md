---
layout: post
title: "Reflections on FOSS"
---

Analyzing open-source ideologies in this way shouldn’t be a surprise to me, and it isn’t exactly, but I’ve definitely never thought about software development through this lens before. I’ve hardly ever worked on software development projects before, apart from CSCI 362 last semester where an emphasis was placed on how adding developers to a project often made it take longer rather than cutting time off of the project. Even though we worked on open-source projects in that class as well, I feel like many readings in 362 addressed software development in a more corporate structure, or at least didn’t explicitly contrast open-source development with closed-source coding.  

That said, I think “The Cathedral and the Bazaar” provides a really useful perspective for project organization when it comes to working with large teams. Of course open-source software isn’t limited to large teams, and many projects are driven forward by small teams over time, but I think this is where some of the guidance from building code up “Bazaar” style can really shine (more to come on how it can apply to smaller teams as well).  

The article notes how for a project to successfully transition to Bazaar-style development, there must be an existing product or foundation to work from. This is important so that everyone working has a clear focus and rooted goals. Beginning this type of development without a core concept and code would not be productive because when a project still has the potential to become anything, it would be impossible to focus the collective attention of a large group of independent contributors. While this may eventually result in a viable product, it would likely turn out to be a poorly stitched together pile of code from various components which were never intended to work together or complement one another.  

Provided a core code base however, the style of organization common in Bazaar-style software development can be useful regardless of whether it is being used in an open source or corporate environment. This is largely due to the practice of having many sets of eyes on any individual piece of code rather than only one person or a small team working on each piece and fitting all of the pieces together. Every student knows that after you look at your own work for long enough it gets more and more difficult to see any errors because you are so familiar with your work that your brain fills any gaps with what you assume to be true. Breaks from your work can help but the only way to make sure these gaps have been accounted for is to have multiple sets of fresh eyes with their own experiences and perspectives to provide analysis and edits. And to not let ego get in the way during this process.  

This is where Bazaar-style development can also help smaller teams. Sometimes it may make more sense to divide work so that more ground can be covered, but it is also necessary for small teams to review each other’s code for correctness and efficiency if large strides are to be made. Additionally, the principle in Bazaar-style development where users get to find, pick, and choose which parts of a project most interest them. Of course this won’t always be possible, especially with a small team where a portion of an app or project may not be a strong interest of anyone on the team, but if anyone does feel strongly about a particular component and brings relevant experience to the table, they will be significantly more motivated and productive if they are able to capitalize on this area of interest.  

---

Tennants from "The Cathedral and the Bazaar" by Eric Steven Raymond  

1. "Every good work of software starts by scratching a developer’s personal itch."

2. "Good programmers know what to write. Great ones know what to rewrite (and reuse)."

3. “Plan to throw one away; you will, anyhow.” (Fred Brooks, “The Mythical Man-Month”, Chapter 11)
 
4. "If you have the right attitude, interesting problems will find you."
 
5.  "When you lose interest in a program, your last duty to it is to hand it off to a competent successor."
 
6. "Treating your users as co-developers is your least-hassle route to rapid code improvement and effectivedebugging."
 
7. "Release early. Release often. And listen to your customers."
 
8. "Given a large enough beta-tester and co-developer base, almost every problem will be characterized quicklyand the fix obvious to someone."
 
9. "Smart data structures and dumb code works a lot better than the other way around."
 
10. "If you treat your beta-testers as if they’re your most valuable resource, they will respond by becoming yourmost valuable resource."
 
11. "The next best thing to having good ideas is recognizing good ideas from your users. Sometimes the latter isbetter."
 
12. "Often, the most striking and innovative solutions come from realizing that your concept of the problem was wrong."
 
13. "Perfection (in design) is achieved not when there is nothing more to add, but rather when there is nothing more to take away.”
 
14. "Any tool should be useful in the expected way, but a truly great tool lends itself to uses you never expected."
 
15. "When writing gateway software of any kind, take pains to disturb the data stream as little as possible – and*never* throw away information unless the recipient forces you to!"
 
16. "When your language is nowhere near Turing-complete, syntactic sugar can be your friend."
 
17. "A security system is only as secure as its secret. Beware of pseudo-secrets."
 
18. "To solve an interesting problem, start by finding a problem that is interesting to you."
 
19. "Provided the development coordinator has a medium at least as good as the Internet, and knows how to leadwithout coercion, many heads are inevitably better than one."
