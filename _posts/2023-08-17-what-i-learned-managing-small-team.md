---
layout: post
title: "What I learned after managing a small team for 2 years"
permalink: /managing-small-team
---

For the past 2 years, I've been leading a team of 4 engineers: 3 developers (including myself) and 1 QA. This is the first time I've managed a software team, after writing software full-time for 6 years. Here are some things I've learned during that time.

### Get to know everyone, and take note of _what_ should change and _why_ (if anything)

Looking back, there was one thing I _should_ have done but didn't do: hear the team members' thoughts about the leadership changes. I just naturally understood what they expected of me and what things did and didn't work under the previous leader. If I had to do it all again, I would have immediately sat down with each team member individually to hear their thoughts about:

* What were some things _they_ would like to see changed? 
* What things were working well enough that _shouldn't_ change, and maybe just tweaked/improved?
* What do they _personally_ expect from a new team leader?
* Is there anything I could do to improve their day-to-day work?

Had I done this, it would have saved me a couple of months of time of figuring out all of this by myself in a natural way. Of course, I had a couple of meetings with the previous leader and we discussed some things that should change about the team's processes. That input was also valuable! If you are taking over a small team and you have the opportunity to talk with the previous leader, please do! If they have been on the project long enough, they have a lot of context and insights that can be invaluable to you.

### Don't change everything at once

The first two weeks on the project were spent side by side with the previous team leader, where I tried to learn everything about the project, its processes, tools and systems, and, most importantly, the client. After those two weeks, I already had an idea of some things I wanted to improve and/or change, but I made a point not to start doing everything at once. Every couple of weeks, I would talk to the team and show them what I was intending to change and hear their thoughts: what do _they_ think about it? Would it be a hindrance to them? Do we need it? 

The nice thing about leading a small team is that it is very easy to gather input from everyone in a more detailed manner. There's time to hear everyone and to consider every opinion. After presenting the ideas and hearing the feedback, I considered whether or not to go through with the changes. 

And so, week after week, one small tweak after the other, I introduced the changes without disrupting too much of everyone's work. I had the time to assess whether or not the changes were effective and could roll back if needed. 

### Agile is not always the answer

When I talked with the previous team leader, one of the very first things I was told was that "the team needs some form of sprint system". I was happy to hear this, because up to this point, all the projects I had worked on followed the same process, so I was confident I could implement it without too much effort.

The previous system the team was following was something very close to a Kanban system. There was a Trello board with backlog tasks, ongoing tasks, tasks on review, and tasks being tested. In the beginning, I tried to implement a sprint system with Trello, but that didn't work very well, so we migrated to Jira, which we're still using today.

However, looking back, I don't think we _needed_ agile or sprints. The project is not _big_ enough (in scope and size) to justify a system like that. But most of all, agile doesn't fit in the context of this particular project, because the client changes priorities very frequently. As in, _weekly_, and sometimes _daily_. So sprint planning goes out the window every week when new requirements and priorities are discussed. We still use sprints today, but they are nowhere close to the definition of a sprint in a truly agile system. It's something I need to change eventually, but haven't gotten around to doing it.

### Documentation is everything

Before I joined, there was little documentation on _anything_ at all. Tasks that were run in production were kept in one of the team members' notes. Requirements were stored in Slack messages. Conventions, like git commit messages, pull request descriptions, and merging strategies were _verbally_ agreed upon. Code documentation was non existent.

So, I asked the team to send me all their notes and I documented everything in a Confluence space. It was nice seeing the knowledge gathered by each team member over the years written down in a place where everyone could see it. Ticket requirements weren't lost anymore in the sea of Slack messages and threads, and could be more formally discussed with the client using the comment system on Confluence. The most important thing here was that I didn't put this burden on the team members. I took the time to write it all down and _then_ asked the team for feedback. Of course, once this was set in place, I made a point to ask the team members to, from then on, document everything on Confluence. Every piece of written documentation would go into Confluence and then be triaged to the correct category. 