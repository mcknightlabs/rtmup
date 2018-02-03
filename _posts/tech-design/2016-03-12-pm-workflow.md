---
layout: article
title: Project management workflow
description:
category: tech
tags: 
- management
- tech
---

<p>UPDATE Jan 2017: The workflow described in this post has been replaced with one centered around JIRA and Confluence.</p>

<p><em>This is the first post in a series about my project management workflow – how I wrangle problems, goals, and deadlines.</em></p>

<p><strong>The biggest project management problems I face are as follows:</strong></p>

<ol>
	<li>Organizing/prioritizing the massive amount of project-related information I receive</li>
	<li>Keeping track of who is working on what project task and the progress that's been made</li>
	<li>Maintaining a birds-eye-view of all ongoing projects</li>
</ol>

<p><strong>Here's a list of strategies I use to address those issues:</strong></p>

<ol>
	<li>Constant email prioritization</li>
	<li>Constant Trello project and task management</li>
	<li>Constant Github project and task management</li>
	<li>Daily design team stand-up meetings</li>
	<li>Weekly check-in meeting with the CTO</li>
	<li>Weekly check-in meeting with the entire company</li>
</ol>

<h3>1. Constant email prioritization</h3>

<p>Each day, I receive dozens of emails about ongoing and upcoming projects, new feature ideas, bugs, etc. I keep track of all of these to-do emails in two ways.</p>

<p><strong>1) I use Gmail's multiple inboxes feature.</strong></p>

<p>I currently have four inboxes: 1) Inbox 2) Action needed 3) To read 4) Useful</p>

<figure>
	<img src="{{ site.url }}/media/img/tech-design/2016-03-12-pm-workflow/multi-inboxes.jpg" class="img-border">
</figure>

<p>Every new email goes in the main inbox.</p>

<p>If I can quickly follow up, I immediately shoot off an email. If not, and I still need to act or reply, I move it to "Action needed."</p>

<p>If it's an article or newsletter – e.g. Nieman Lab, Both Sides of the Table, Fred Wilson, etc. – I add the label "To read" and move it to that inbox.</p>

<p>Emails that contain info I might need at a later date - e.g. interviewing tips, instructions on how to get a particular virtual environment running, etc. – I send to the "Useful" inbox.</p>

<p>H/T to <a href="https://twitter.com/blakeir">Blake Robbins</a> for this technique. He wrote a <a href="https://associate.vc/the-best-e-mail-workflow-no-extensions-needed-1eb296eaf069#.ieq04c9fp">great post</a> about how to set up multiple Gmail inboxes and use them to get to inbox zero.</p>

<p><strong>2) I keep a daily updated "agenda" email of this week's tasks.</strong></p>

<p>This email is broken down into two parts: 1) my tasks and 2) the tasks of the people I am managing. Each of these sections is broken down by the day. At the end of the day, or beginning of the next, I update this list with any new tasks I was emailed about the day before.</p>

<h3>2. Constant Trello project and task management</h3>

<p>Trello is a card-based management program I use with my design team to keep track of all design-related projects and their moving parts – the individual tasks. Because we are a startup of 50 with a design team of three, we use a single Trello board for all areas of design: graphic design, front-end, and UX.</p>

<div class="row">
	<div class="medium-4 columns">
		<figure>
			<img src="{{ site.url }}/media/img/tech-design/2016-03-12-pm-workflow/trello-1.jpg" class="img-border">
		</figure>
	</div>
	<div class="medium-8 columns">
		<figure>
			<img src="{{ site.url }}/media/img/tech-design/2016-03-12-pm-workflow/trello-2.jpg" class="img-border">
		</figure>
	</div>
</div>

<p>Projects and tasks are assigned to specific users and due dates added, when applicable. After a task is finished, the assignee moves it over to a "done" card stack. We do this, rather than archive it, in case we need to pull it back to a live stack. It happens, on occasion.</p>

<p>My team also uses a few Chrome extensions for extra functionality: <a href="https://chrome.google.com/webstore/detail/card-color-titles-for-tre/hpmobkglehhleflhaefmfajhbdnjmgim?hl=en">CardColor Titles</a> and <a href="https://chrome.google.com/webstore/detail/cardcounter-for-trello/miejdnaildjcmahbhmfngfdoficmkdhi?hl=en">CardCounter</a></p>

<p>CardColor Titles allows us to add useful priority/status labels. CardCounter gives us an idea of how many tasks/projects there are in a given card stack.</p>

<p>Aside: I also use Trello for onboarding; there's a "first week" list that the new designer must go through. It covers what accounts and software she or he will need to set up + links to tutorials to fine-tune particular skills.</p>

<h3>3. Constant Github project and task management</h3>

<p>When managing any front-end project or associated task, I turn to Github. Github "issues" are easy to track and comment on. Our team also has Github integrated with Hipchat, our instant messaging service, so we receive alerts about new issues and status changes.</p>

<p>Here's a brief overview of how I create project and task issues in Github:</p>

<ol>
	<li>Write a short summary of the problem</li>
	<li>Upload a screenshot of the problem, if necessary</li>
	<li>Write a short description of an agreed upon or possible solution</li>
	<li>Add status labels (e.g. high-priority, front-end, etc.)</li>
	<li>Assign myself or a team member</li>
</ol>

<h3>4. Daily design team stand-up meetings</h3>

<p>I started out having weekly design team meetings on Monday mornings and keeping tabs on ongoing projects via Trello and Github. As the design team and number of projects grew, I transitioned to having these daily.</p> 

<p>During the 10-15 minute meeting, each team member gives an update about the projects and tasks s/he is working on.</p>

<p>Many of you are probably familiar with this technique. It's a common component of Agile software development frameworks like <a href="https://en.wikipedia.org/wiki/Scrum_(software_development)">Scrum</a>.</p>

<p>I actually borrowed this management approach from our tech team.</p>

<p>Aside: our CTO has a pretty great philosophy on management and tech frameworks – use what works for you. Take the best and leave the rest.</p>

<h3>5. Weekly check-in meeting with the CTO</h3>

<p>Each Monday, I open up a new email and compile a list of open, design-related Github pull requests and other projects that my team needs the tech team's help with.</p>

<p>I then meet one-on-one with our CTO. He and I spend 10-15 minutes going over the list. It's mainly an opportunity for me to explain the PRs in a bit more detail, talk about priorities, and check in on the status of larger projects (e.g. projects that involve A/B testing or multiple moving parts/PRs).</p>

<p>After the meeting, I then send him the email and bcc myself for reference.</p>

<h3>6. Weekly check-in meeting with the entire company</h3>

<p>The company check-in is a founder organized, 30 minute mandatory meeting every Monday morning. These have been held since year one. They're a way for the heads of all the departments and the company founders to let everyone know about the existence and status of ongoing and upcoming projects.</p>

<p>The need to prep for this meeting led me to create the daily-updated "agenda" email I mentioned earlier.</p> 

<hr class="divider">

<p><em>The next post in this series will cover my project management approach to new product features.</em></p>