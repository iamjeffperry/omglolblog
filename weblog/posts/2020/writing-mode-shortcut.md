---
title: Writing Mode Shortcut
date: 2020-04-17T20:00:00-0400
---

# Writing Mode Shortcut

After making writing a routine for this newsletter, I wanted to automate things a bit so that I can get into the [writing flow](https://www.writersdigest.com/wd-books/on-writing-fiction-excerpt) even faster. After some tweaking, I think I have finally created a version 1.0 of my Writing Mode Shortcut.

![](https://jeffperry.b-cdn.net/15526fb897.jpg)

Essentially, this Shortcut sets the brightness and volume where I want it, creates an event called “Writing” in my calendar, sets Do Not Disturb, Opens Drafts, and adds a word of encouragement before I get started.

Here’s a breakdown of each item.

Set Volume
----------

When I am writing, I like to have my volume loud enough to hear it, but not loud enough where it distracts my thought process when writing. After some trial and error, 20% is about where I need it to hit that sweet spot.

Set Brightness
--------------

Like the Set Volume action, I like to make sure my iPad is at the brightness level I prefer for writing. To me, 70% seems the be the brightest I want my iPad when I am in my office writing.

Add 30 Minutes to Date
----------------------

This is an action that I use as a later variable. I use it as a custom Pomodoro technique.

When I first start writing in the morning, it can be daunting to look at a blank page. When I am in that mood, I often use the [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) to get myself going. The first step in creating a custom Pomodoro Timer in Shortcuts is with this action.

This action works by taking the current date and time and adding 30 minutes to it. From there, I use it in the next action to create an event.

You can always adjust the time in this to your preference if you so choose.

Create Event
------------

With the adjusted time, I create an event called “Writing” in my calendar that starts immediately and ends 30 minutes later using the Adjusted Date as a Magic Variable.

Set Do Not Disturb on Until Event Ends
--------------------------------------

Once that event is created, I use it as a Magic Variable as well for setting Do not Disturb on. After the event is created, I turn on Do Not Disturb and set it to turn back off once the newly created event has ended.

I was initially going to use a simple timer for this Pomodoro Technique.

Still, I realized that I wanted to keep track of how must time I was using to write, so I decided to use the calendar as a means of record-keeping.

Of course, I don’t always hit this Shortcut every 30 minutes, so I adjust it later to reflect the actual amount of time I was writing, but it is a good starting point for me to track my writing.

Open Dark Noise and play Coffee Shop
------------------------------------

[Dark Noise](https://apps.apple.com/us/app/dark-noise/id1465439395) is an app that adores using when in the writing spirit. I use it when I need to focus while working. If you don’t know, Dark Noise has many soundscapes you can listen to to help you concentrate, sleep, or fill your ears with something.

I often use the Coffee Shop sound when I am writing. If I could go out to an actual coffee shop, I wouldn’t be using this app. Alas, because we are in the pandemic, this soundscape will make due for the time being.

Open Drafts
-----------

Once I have everything set, it is time to get writing! The app I use when writing is unsurprisingly [Drafts](https://apps.apple.com/us/app/drafts/id1236254471). This Shortcut action opens the Drafts application. The way that Drafts works is that if you open the app, it usually starts with a blank page waiting for you to start writing, which is what I want.

If I indeed need to open something I have been working on, it is stupidly easy to open up the drafts list and search for what I need and open it up.

I originally wanted to make this a list of items to choose from. However, after some time with it, I noticed that when I give myself the barrier to decide before I begin writing, it negatively affects my ability to get into the writing flow. So, I decided that I will open a new draft and start writing. It is more critical for me to get into the flow than to be in the right doc.

Once I am editing or taking a break from writing, I can figure out where this writing goes, but for “Writing Mode,” my main priority is writing.

An Encouraging Notification
---------------------------

Finally, I wanted to have a list of different words of encouragement for me to use to get started. So far, I threw in a few simple things in a list.

With this list, I then have it choose a random one and display it as a notification. It is just a small thing that helps me get into a positive mood and trick my brain into being excited to write, even though it’s 5 am.

You can [download the Shortcut here](https://www.icloud.com/shortcuts/8bdf0e4d5db0413686cf8fb3e2e106b8) and start to make it yours today.