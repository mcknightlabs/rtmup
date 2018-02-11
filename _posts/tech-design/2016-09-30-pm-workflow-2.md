---
layout: article
title: Project management workflow v2.0
description:
category: tech
tags: 
- management
- tech
---

<p>UPDATE Jan 2017: The Waffle.io workflow described in this post has been replaced with one centered around JIRA and Confluence.</p>

<h2>Intro</h2>

<p>The design team at Industry Dive is responsible for a lot of varied tasks and projects – from the creation of branded marketing content to the front-end development of news websites.</p>

<p>Managing all of these moving pieces is somewhat of a tricky proposition. And that's great. Constantly tackling difficult challenges is how you grow stronger – "<a href="https://books.google.com/books?hl=en&lr=&id=g5pD9ciNvA0C&oi=fnd&pg=PA43&dq=Motivation+by+goal+setting&ots=uUSGmEBIwq&sig=ppzQxsBoi0frkHWGigAM9PWTp2I#v=onepage&q=Motivation%20by%20goal%20setting&f=false">the more difficult the goal, the higher the performance achievement</a>."</p>

<p>So what's my project management process? Let's start from the top...</p>

<h2>Goals</h2>
<ul>
	<li>Maintain a birds-eye-view of all ongoing projects</li>
	<li>Easily be able to create, prioritize, and assign new projects and tasks</li>
	<li>Track task assignments and project progress in a way that is scaleable and not overly burdensome on myself or team</li>
</ul> 

<p>To accomplish these objectives, I organically came up with the approach I wrote about in this <a href="{% post_url tech-design/2016-03-12-pm-workflow %}">March 2016 post</a>.</p>

<p>Since that time, my tactics have evolved quite a bit.</p>

<h2>Snapshot of my updated management process</h2>
<ul>
	<li><span class="strike-through"><del><strong>"Action needed" Gmail inbox:</strong></del></span> I have been using Gmail's "multiple inboxes" feature for most of 2016 in an attempt to better stay on top of ongoing projects and keep my inbox near 0. My initial approach was to split my inbox into 4 sections: 1) Inbox, 2) Action Needed, 3) Useful, and 4) To Read. Recently, I reassessed this technique and decided the "action needed" inbox was non-essential. I found I could just "star" emails in my inbox – as an "action needed" reference – and still keep my inbox down to 10-20 messages.</li>
	<li><del><strong>Running e-mail of team member assignments:</strong></del> For about two years, I kept track of all team member assignments in a single email. I did this because we were using several different project management tools and this was the best way to give myself a high-level view of team activity. In the end, it proved an unsustainable and unscaleable method.</li>
	<li><del><strong>Trello + Basecamp + Github + Email</strong></del> Using multiple project management tools can create all sorts of <a href="{% post_url tech-design/2016-08-17-burnout %}">pain points</a> and headaches. Over the past couple of months, I spent a good deal of effort moving my team to a single platform – Github.</li>
	<li><strong>Github:</strong> For a long time, I primarily viewed Github as a tool for managing web issues – e.g. front-end design changes – that I want version-controlled. Recently, I decided to leverage the platform to keep track of our graphic design projects too. A dedicated "design" repository now enables our team to manage non-front-end related design issues. Because all of our design issues are on a single task/project management platform, I no longer need the running email previously mentioned.</li>
	<li>
		<strong>All Github issues are visualized via Waffle.io:</strong> 
		For several years, the design team used Trello to keep track of all of our tasks and projects. When we started tracking graphic design projects on Github, it made sense to reassess our use of Trello. After some experimentation, I found Waffle.io offered us a few more advantages than Trello:
		<ul>
			<li>
				<strong>Tighter Github integration:</strong> The design team can quickly view Github issues across a range of repos. Changing an issue label – e.g. "ready for design" – on Waffle also changes that label on Github.
			</li>
			<li>
				<strong>Already used by tech team:</strong> Using the same management tool as other teams in the company ensures closer and easier collaboration and the opportunity to share lessons learned.
			</li>
			<li><strong>Personalized view:</strong> Each design team member can now filter issues by their Github handle and see only the issues assigned to them.</li>
			<li><strong>Birds-eye-view of process:</strong> Each design team member can see where different issues are in the process toward completion.</li>
		</ul>
	</li>
	<li><strong>Daily standup meeting:</strong> Every morning, the design team meets and each person talks for 5-10 minutes about which tasks and projects she or he is in the process of working on that day. This facilitates collaboration, quickly surfaces pain points, and allows for a given day's priorities to be clearly communicated.</li>
	<li><strong>Weekly company meeting:</strong> The company still holds these meetings every Monday, but they've evolved a bit since March. Rather than only asking team leaders to give updates about ongoing projects, the invitation is now open for any employee to speak up and share important news with the rest of their coworkers.</li>
	<li><strong>Google form for editorial graphic requests:</strong> Editorial graphics requests – e.g. bar chart for a news article – used to arrive about 10 different ways – e.g. in-person request, email, Hipchat, etc. – to four different team members. This was terrible. It made it likely that some tasks would not receive the timely attention they deserved. To fix this issue, I set up a a single Google form for editors to submit requests. Form submission triggers a notification email sent to myself and one other team member.</li>
	<li><strong>Google form for business card and press pass requests:</strong> Same as above.</li>
	<li><strong>Team collaboration documentation:</strong> Some of our design projects require routine collaboration with other in-house teams – e.g. Brand Studio, tech, and editorial. To ensure greater consistency and effectiveness in cross-team task and project execution, I put together a Google Doc that details the steps design team members should take when particular design requests are submitted.</li>
</ul>

<h2>Lessons learned along the way</h2>
<ul>
	<li><strong>Aim for simplicity.</strong> Use as few project management tools as you possibly can. Cut any non-essential process. The more tools and processes you have, the easier it is for details to fall through the cracks. It's also harder to maintain a bird's eye view of progress, because you are constantly jumping between tools. If you do use multiple tools, make sure they integrate well together.</li>
	<li><strong>Question your intuition when it comes to processes.</strong> Trying to keep a running list of team tasks in an email was 100% unsustainable. I initially used this method because that's what I had done for my personal tasks for years. It felt intuitive. It even worked pretty well for a while. But it was far from the best approach.</li>
	<li><strong>Keep your finger on the pulse of your process.</strong> Be aware of 1) the stress your processes might be causing you or your team and 2) how effective your processes are at helping you get shit done. Although it was far from being the sole factor, my previous approach to project management contributed to an increasing feeling of burnout over a period of a couple months. In response to this realization, I quickly searched for ways to make my process more efficient.</li>
</ul>

<h2>How to keep getting better</h2>
<p>I'm of the mind that the key to getting better at anything is to never settle. When you make progress or hit a goal, you celebrate the moment, assess what worked and what didn't, and then move on to the next task, the next objective.</p>
<p>The end-game here is never perfection – that's a concept that will prevent you from getting shit done. The aim is to always be moving forward more intelligenty.</p>
<p>To that end, here's my high-level approach to "getting better" at project management:</p>
<ul>
	<li>Constantly question your current processes.</li>
	<li>Routinely ask for feedback.</li>
	<li>Automate and delegate as much as possible.</li>
	<li>Study the techniques of other managers and teams.</li>
	<li>Experiment, but not to the extent that constant change is a pain point for your team.</li>
</ul>