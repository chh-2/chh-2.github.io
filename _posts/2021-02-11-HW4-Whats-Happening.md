---
layout: post
title: "What's Happening?"
---

## Teaching Open Source - Chapter 7: Fixing the Code  

### 7.2.2 - Compare diff Formats  

![](https://github.com/chh-2/chh-2.github.io/blob/master/_assets/homework_images/Screenshot%202021-04-06%20133053.png)  

diff -u is much more readable, especially for someone unfamiliar with the code or if larger changes are made. Even for smaller changes, I think if someone was unfamiliar with the code then a basic diff command could be hard for them to parse in a meaningful way.  


### 7.8 - Create a Patch for a New File  

![](https://github.com/chh-2/chh-2.github.io/blob/master/_assets/homework_images/Screenshot%202021-04-06%20134637.png)  


### 7.9 - Patch Echo  

![](https://github.com/chh-2/chh-2.github.io/blob/master/_assets/homework_images/Screenshot%202021-04-06%20135513.png)  

The configure and make commands failed when I tried to run them, so I was unable to test this change.  

---

## Reflections on "Behavioral Science of Software Engineering"  

To describe software development as a "sociotechnical activity" probably sounds lofty and abstract to a lot of people. ‘Socio’, to do with society or social structures; ‘technical’, to do with technology. Seems obvious, right? But what does this even mean? What implications does it hold?  

As a computer scientist who also studies sociology, philosophy, and psychology, the relevance of social concerns to an industry as large and dynamic as software development cannot be understated. This article; as an introduction, overview, and summary of the other articles contained within this issue of the publication; may not go into a deep dive itself into any particular issue, but it serves largely to demonstrate the breath of issues that social science can influence in software development.  

Ageism, gender gaps, social media, interviews, data logging. Developers have physical, social, and emotional needs that can directly influence their work, or that can be directly influenced by their place of work. As noted, however, out of more than 50 submissions, there were few if any submissions involving the politics of algorithms, the implications of software in regulatory frameworks, or social and behavioral aspects of new technologies. Issues like ‘racial profiling’ are already rampant in the consumer market. I had a friend whose fitness tracker couldn’t detect their heartbeat unless they wore a slip of paper between the sensor and their skin. There can’t be trust for facial recognition software to identify faces of different genders, ages, and races if something as simple as a heartbeat sensor fails based on the color of someone’s skin.  

Other concerns exist from the consumer’s view as well. One I’ve seen joked about is how self-driving cars rely on the basic functionality of (among other things) being able to identify and respond accurately to a stop sign. Identifying a stop sign is still a basic test many websites use to determine whether a visitor to the site is a human. Yes, the technology has advanced rapidly and yes, it is significantly more sophisticated than most bots on the internet, but that doesn’t necessarily matter depending on the social aspects of how this software is presented to a common person. As technology that has physical consequences for failing becomes more and more integrated into daily life, these types of concerns will have to be addressed and PR managed, which will vary based on the social context of a country or region. This is especially important to consider as corporations increasingly operate at a global scale.  

As far as the development side of things, of course diversity in developers is important in achieving a satisfactory level of representation (including among the customer/user base). But it can’t just be tacked on as a requirement for hiring teams or as a development specification with no deeper thought. There needs to be a level of empathy and human connection between the developer and the person they’re developing for in order to help bridge the gap. Some of this can be seen in classes on UI/UX design, or other ‘softer’ areas of development. But including these types of considerations in planning and development means certain things don’t have to be tacked on as an afterthought. Accessibility features, for instance, can be included in the design of certain software from the start. Representation of a wider customer base should be considered in testing software.  

It’s not just about tech anymore. We can no longer ignore these sociotechnical interactions and just how significant they are in the direction and influence of software development as a social force.  


--- 

M. Petre, J. Buckley, L. Church, M. Storey and T. Zimmermann, "Behavioral Science of Software Engineering" in IEEE Software, vol. 37, no. 06, pp. 21-25, 2020.  
doi: 10.1109/MS.2020.3014413  
keywords: {}  
url: https://doi.ieeecomputersociety.org/10.1109/MS.2020.3014413  
