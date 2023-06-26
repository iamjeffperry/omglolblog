---
title: How Daily Notes Changed Everything for Me
date: 2021-06-27T20:00:00-0400
---

# How daily notes changed everything for me

I have been on a note taking journey for some time, and its been both interesting and precarious. While I may not have finished this adventure yet, I have learned the value of daily notes.

  

This week, I want to share with you what they are, how I am using them, and how daily notes can be a benefit to you.

  

What Are Daily Notes?
---------------------

  

Daily notes are pretty self-explanatory for the most part. They are notes you write in daily, with each note being the day’s date. It’s that simple, at least by definition. What you _do_ with the daily notes can be very complex if you want it to be.

  

I learned about Daily Notes years back but it never quite “clicked” with me. There were apps like [Agenda](https://agenda.com/) that were all about having daily notes and there were people using Drafts just for this purpose. Some used it to journal, others used it for task and project management, or a bit of both.

  

At the time, it seemed interesting but I had no interest in categorizing my notes by date. It stayed that way for me until I started to use [Obsidian](https://obsidian.md/) and enabled the [Daily Notes](https://help.obsidian.md/Plugins/Daily+notes) core plugin.

  

Ever since then, daily notes has been my most frequented place in my notes. I rely on it to keep my tasks in check, capture _everything_ I come across, and even as an agenda for what I have happening today and a log for what I did that day.

  

Greg Morris had a [nice article](https://gr36.com/2021/06/24/using-craft-for.html) about daily notes and explained them perfectly saying:

  

> [Daily notes](https://www.gr36.com/2021/05/15/my-obsidian-set.html) is a practice that I preach to almost anyone that will listen, the one thing that remains form [my time using Roam Research](https://www.gr36.com/2020/08/21/how-to-start.html). In these I record almost everything that happens during my working day, such as telephone calls, things I am thinking, interactions I have had and anything else I think I might need to refer back to later. This allows me to just get things out of my brain at the time they pop up so I can act on them later, or refer back to them if needed.

  

Once I learned about the power of daily notes, I started to think about how to maximize their value and remove any friction I could have when making these notes. Thankfully, Obsidian has an impressive set of options you can use to make daily notes populate automatically and even have templates set up. There are other options as well that deserve mention, namely [Craft](https://www.craft.do/) and [Drafts](https://getdrafts.com/). If you want to look into those apps you can take some of what I write here with you as well.

  

I want to share with you my daily notes setup, some tools and resources I recommend, and show why you should consider daily notes for yourself as well.

  

My Daily Notes Template
-----------------------

  

My notes template isn’t anything special, but I think it is a great starting point for many looking to use Obsidian, or another app, for daily notes.

  

Here’s what my daily note template looks like:

  

![](https://jeffperry.b-cdn.net/20cccc17d3.jpg)

  

If you want to learn more about templates you can find a bunch of great information from [Obsidian help and support documents](https://help.obsidian.md/Plugins/Templates).

  

Let’s break this down for each section in the template.

  

### Tasks

  

The first thing I have in my template is tasks. I use this for two instances of task management: the tasks I _assign_ to do today and the tasks I created today.

  

For the former, I user an embedded search with the plugin [Vantage](https://github.com/ryanjamurphy/vantage-obsidian) and their search query. It sounds like a lot, but basically this plugin is used to allow users to create custom searches that finds instances in their notes library that fit their search. Once you have one made that you want to use you can embed that search into a template and use it every time you create a new note with said template.

  

For me, I wanted to find every incomplete task that is due on today’s date. I might have a document that has a task in it that I have assigned a due date like [2021-06-27](2021-06-27  "wikilink"). With this embedded search set up in my template, I create the daily note for June 27th, 2021 and the search query populates looking like this:

  
```query
(line:(/- \[ \].*.*/))
```

  

What that shows is this:

  

![](https://jeffperry.b-cdn.net/4243a5fec1.jpg)

  

There’s more you can do with this for tasks, but you can learn more about Vantage and how to use it on [their GitHub page](https://github.com/ryanjamurphy/vantage-obsidian).

  

For the tasks I create that day I just input them as the following:

  

```
- [ ] this is a task
```

  

From there, I will process any incomplete tasks and move them to either the next day or assign them to another date. It is also very possible I decide the task I created is no longer worth my time and I just delete it entirely.

  

It might seem pointless for me to make a task only to delete it later but at the time I put it in I wanted to do that task, but after some time settled and I thought more in the processing phase I deemed it not to be worth my time, effort, or both.

  

### Reading List

  

One thing I also use Vantage for is a reading list. Instead of using a date to find notes, I use tags.

  

Tags in Obsidian aren’t too different than tags in other apps you have used. For me, I use `#readlater` for all the articles, videos, and more that I want to capture in Obsidian and read later. There are two ways you can add tags to a note in Obsidian.

  

You can either use tags inline with text like `#readlater` or put it in the front matter of the note, which is as simple as having the following at the top of your note:

  
```
---
tags: readlater
---
```
  

Either way, once you have a specific tag set up for your reading list you can use Vantage to create this embedded search.

  

![](https://jeffperry.b-cdn.net/5420d927e8.jpg)

  

Once I have it the way I want, I click “Create embedded search” and it will paste it into my note.

  
```
(tag:#readlater)
```

  

It looks very similar to my other embedded search, but you can see that it uses tags rather than dates in the query.

  

When I change it from editing mode to preview mode (using Command-E ) I see something like this:

  

![](https://jeffperry.b-cdn.net/bf344f6f6c.jpg)

  

Once I add the embedded search to my daily notes template it will populate all notes and text with the tag `readlater`.

  

### Notes

  

Finally, Notes is a catchall for everything I find, think of, or want to remember. It is my scratchpad for all links, ideas, events, etc. that I want to make sure I capture before it leave my mind. I also have been dabbling in writing out journal entries from time to time as well.

  

Once I know it is in this notes system and I have it written down somewhere i can allow my mind to relax and focus on coming up with ideas rather than keeping them.

  

David Allen, author of _Getting Things Done_ once said “Your mind is for having ideas, not holding them.” I often think about this quote and I use it to remind me just how important it is to have a trusted system for you ideas, tasks, and everything else. I am not saying Obsidian is the _perfect_ app for all of those things, but Obsidian has become a bigger part of my trusted system for some time now.

  

As for what happens to all of my notes, tasks, etc. I process them either at the end of the day or first thing the next morning.

  

Quick Capture
-------------

  

I really wanted to show Quick Capture in action on iOS 15 but as of right now, I can’t seem to get beta 2 to work with Shortcuts reliably. At times it works, but at other times it doesn’t. Sadly, for that reason, I can’t in goo conscious share anything iOS 15 related

  

However, if you are on iOS 14 and want a way to make it happen right now, all you have to do is follow this video [Curtis McHale](https://curtismchale.ca/) streamed a week back and it will help. The catch is you need to use the app [Toolbox Pro](https://toolboxpro.app/) in order for this to work for you. It uses a neat workaround for you to append files outside of the Shortcuts folder.

  

https://youtu.be/gFN1441KNCI

  

With Curtis’ shortcut you can even take it a step further and get things from Safari like the page Name, Author, publication date, etc. and use that in a shortcut to have everything you need all in one spot. The opportunities for growth and tweaking are endless. If you end up making something awesome [let me know on Twitter](https://twitter.com/iamjeffperry), I would love to see!

  

There is also a workflow from Mike Schmitz over on _The Sweet Setup_ where he shows [how to use Drafts with Obsidian for quick capture](https://thesweetsetup.com/appending-captured-text-in-drafts-to-daily-notes-in-obsidian/).

  

The nice thing about Obsidian is that it is a notes app built around markdown files. It is just plain text, and because of how simple it is there are lots of different ways to add, edit, and append to the files.

  

I hope that iOS 15 allows for these workarounds to be obsolete, but until then there are a couple ways for you to add to your Obsidian daily notes.

  

How Daily Notes Help
--------------------

  

So, what is the point of daily notes? Why bother with all of this setup? Here’s a few things you can benefit from with them.

  

### Remember it Now

  

I am a huge fan of [Field Notes](https://fieldnotesbrand.com/). They are small notebooks that I keep in my pocket to write down things when my phone isn’t going to cut it for me. Their motto has always been a mantra for me, “I’m not writing it down to remember it later, I’m writing it down to remember it now.” I have always kept that in my mind over the years because it reminds me that my brain isn’t going to remember this later so I _need_ to write it down now.

  

If you are someone that wants to be more diligent in notes and capturing the things that you want to remember, daily notes is a perfect way to do that. Before I was using daily notes, I was relying on my brain to remember and save all of the things that I would think of in a day. This is a _horrible_ system. I lost count how many times I would forget a thought I just had minutes prior. If I had daily notes, or a notes system I trusted, I could have written it down and saved myself the trouble. Now, with this system I am able to drop links, ideas, and tasks without worrying about forgetting them.

  

### Daily Log

  

Another benefit with daily notes is that I now have a log of what I have done for the day. Before, I would often go to bed feeling like I hadn’t accomplished much for that day. I would feel unfulfilled, wish I had worked harder. Over time I began to feel like I wasn’t doing enough, until I started logging what I was doing each day.

  

What I learned by logging what I was doing was that while I may not have something tangible to show for my work every day, I was indeed making small incremental changes moving the proverbial needle forward to reach my goals. I took nothing for granted, everything I was doing needed to be logged no matter how small it was. After a short time, the feeling of inadequacy and failure washed away all because I was making a conscious effort to write down everything I was doing each day.

  

### Journal

  

I mentioned journaling earlier, and it is similar to the daily log, but I wanted to harp on this a bit more. Journaling can [be beneficial for your mental health](https://www.urmc.rochester.edu/encyclopedia/content.aspx?ContentID=4552&ContentTypeID=1). It can help reduce anxiety, reduce stress, and cope with depression.

  

For me, I never got into journaling until I started to use it in my daily notes. It was a game-changer for me. I really felt that, similar to the daily log, I was able to process my emotions and concerns in a more fully-thought-out way. Instead of having anxiety without knowing what may be causing it, I am able to look at my journal and see why. For instance, between my daily log and my journaling I can see that I had a lot on my plate the last several days and that could be the reason why I have been uneasy every time I sit down to do some work.

  

I don’t write mountains of text in my journal. I simply write how I am feeling, what I did to help with it, and how I felt about the day. It is as simple as a few sentences a day.

  

Conclusion
----------

  

Daily notes aren’t something new, but they are new to me. After some time with them I have seen the benefits of them already, and I am sure I will see other implementations going forward that will inspire me.

  

If you are looking to have a notes system you can trust to capture ideas and resources, be a journal for your life, and log the things you did each day give daily notes a chance.

  

If you are using daily notes please let me know how you are using them by either emailing me [jeff@clicked.news](mailto:jeff@tablethabit.com) or [DM me on Twitter](http://twitter.com/iamjeffperry).