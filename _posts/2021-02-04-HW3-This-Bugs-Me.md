---
layout: post
title: "This bugs me"
---

## Teaching Open Source - Chapter 6: Debugging the Code  

### 6.4 - Find the Oldest Bug

Some of the oldest issues in our project are accessibility issues. These specifically deal with Voice Over compatibility and Colorblind support. Other old issues are feature requests. The oldest issue specifically marked as a bug is that the Android widget only supports the top level of daily checklists and doesn’t facilitate sub-tasks. This issue has been around since 2016/17.  

The user, bringing experience from the app’s web UI, expected to tap on a checklist item with sub-tasks and have it open into a longer checklist that could then be interacted with. What happened instead was that the user would tap on the check list item and all sub-tasks would be marked as complete. Not only was this not the desired effect, but additionally the user was not able to correct the results of this behavior from the widget; they had to open the app either on their phone or in a web browser to un-check the items that had not yet been completed.  

One part of the reason the issue hasn’t been fixed yet probably has to do with it being a widget issue. From what I’ve gathered over the course of this semester, interactions between app data and what displays in a widget are similar but distinct to coding directly within the app. The graphical portion of the app has to correctly pull information from within the app, but has a limited area to display and is built up differently than the app pages which seem to have .xml layouts. It probably also isn’t prioritized as highly given that the functionality exists within the app but not everyone uses widgets.  


### 6.5 - Create Your Bug Tracker Account  

Habitica uses GitHub as its issue tracker.  


### 6.6 - The Anatomy of a Good Bug Report  

We have actually considered looking at the bug described above. After attempting to reproduce sync issues related to several other bugs and not being able to reliably reproduce them, the widget issue was easily reproducible.

```
Description:	Checklist widgets do not behave as expected.
Summary:	When selecting a checklist item with subtasks from a Daily or To-do widget, all subtasks are checked off immediately on selection. 
Version:	3.2.2 (2892)
System:		Moto g Power; Android 10
```


### 6.7 - Bug Triage  

Bug reporting for Habitica isn’t set up with an active triage plan as far as I can tell, at least not for the Android app. There are several ways for a user to submit a bug: either directly in the app, through email, or through GitHub directly. Issues that are submitted through the app or email don’t seem to be added to the GitHub issues list until they have been triaged by the primary developers. There do seem to be several issues related to refreshing certain pages or the app as a whole that don’t all seem to have an independent triage, but some of these are not reliably reproducible. Some of these issues are as follows:  

[Tavern Page Blank](https://github.com/HabitRPG/habitica-android/issues/1479)  
[Coins and Items Don't Update When Selling Thins](https://github.com/HabitRPG/habitica-android/issues/1466)  
[Phantom Pet Eggs](https://github.com/HabitRPG/habitica-android/issues/1460)  
[Progress Not Always Shown in Quests](https://github.com/HabitRPG/habitica-android/issues/1436)  
[Dailies Not Being Loaded When App Starts](https://github.com/HabitRPG/habitica-android/issues/1440)  
