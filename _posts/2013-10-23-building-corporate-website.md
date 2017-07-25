---
layout: article
title: Building the corporate website
description: This post covers our initial project planning and selection of frameworks.
category: blog
age: 23
tags: 
- design
- tech
---

<p>A few months ago, I attended a panel discussion on mobile web design. During the Q&A session, one of the attendees explained that her company had decided to build a new corporate site. She went on to reveal she didn’t know much about web development but had been tasked with leading the project. Then she popped a question that seemed to catch all the panel members off guard— “Where do I start?” The question was clearly outside the scope of the mobile design talk but not surprising to hear at such an event. Confusion during the ‘getting started’ phase is quite common, especially for small companies that don’t have experienced web developers on staff.</p>

<p>So, what’s a good way to answer,”Where do I start?” other than, “It depends”(thanks, Capt. Obvious)? How about an anecdote…</p>

<p>In this post, I’ll give you an overview of how the small (B2B media publishing) startup I work for tackled the tricky, web dev planning stage. Although the decisions at which we arrived are probably different than the ones your team will make, I hope our story can help you get a feel for the high-level strategic questions you need to formulate and the kinds of technical choices with which you’ll be faced.</p>

<p><a href="https://twitter.com/industrydive">@IndustryDive</a>, we kicked off the web dev process the same way almost every other company does — with a meeting. During this initial discussion, we honed in on five key questions:</p>

<ol>
	<li>Which audience(s) do we want the corporate site to serve?</li>
	<li>What is the relative importance of each audience?</li>
	<li>What do we want each audience to know?</li>
	<li>On the homepage, how should we answer the question: “What do we do?”</li>
	<li>What are the problems with our current corporate site?</li>
</ol>

<p>Framing the meeting around these lines of inquiry, we were able to divide our audience into four categories, rank them in order of importance, and determine what information each group would require. This structure also revealed our answer to question 4 — “What do we do?” — would vary depending upon how we prioritized the audience groups. For instance, what we do for advertisers is quite different than what we do for our readers.</p>

<p>I cannot emphasize enough the importance of asking and working through high-level strategic questions such as the ones listed above. <strong>The handful of initial questions you formulate and the answers at which you arrive shape the structure, content, and design of your site.</strong></p>

<p>In the weeks following our first meeting, we added three overarching technical questions to the mix:</p>

<ol>
	<li>Should we build a responsive framework or opt for a dedicated mobile site?</li>
	<li>Should we purchase a template or build the site ourselves?</li>
	<li>Which combination of front-end/back-end frameworks should we use?</li>
</ol>

<p>I’ll briefly address each.</p>

<h3>1) Should we go with a responsive framework or dedicated mobile site?</h3>

<p>Although we already knew we would take a mobile-first approach, our team still needed to decide between a responsive and dedicated mobile site. On the one hand, we knew a single, responsive website could be tailored to look good on most any screen size and would likely provide the company with a more cutting-edge online presence. We also knew it would mean easier site maintenance going forward (only one site to update). In contrast, we thought dedicated desktop and mobile sites would probably be easier and faster to design and develop.</p>

<p>Weighing the various pros and cons, we took the leap and opted for a responsive site.</p>

<h3>2) Should we purchase a template or build the site ourselves?</h3>

<p>Realizing the opportunity cost of building our own site, we spent some time browsing templates. In the end, we didn’t come across any closely aligned with our needs. Also wanting to have a unique online presence, we decided to create something really original. A further added bonus of building the site ourselves was the far greater learning opportunity. No one on the team had ever built a responsive website. — <strong>We ended up learning by buying a few books, reading responsive design articles on the interwebs, and making a lot of glorious mistakes.</strong></p>

<h3>3) Which combination of front-end/back-end frameworks should we use?</h3>

<p>At this stage, we did a great deal of research on various frameworks. Regarding the front end, we checked out everything from bare-bones CSS frameworks like <a href="http://960.gs/">960 Grid</a> and <a href="http://goldengridsystem.com/">Golden Grid</a> to more complex ones like <a href="https://medium.com/">Bootstrap</a> and <a href="http://foundation.zurb.com/">Foundation</a>. After numerous comparisons (we kept a spreadsheet of contenders) and article reading, we ended up selecting Bootstrap. Right out of the box, it offers a lot of useful code for things like mobile menus and a decent responsive framework.</p>

<p>After locking in on Bootstrap, we chose <a href="http://mezzanine.jupo.org/">Mezzanine</a> as the back end <a href="http://en.wikipedia.org/wiki/Content_management_system">content management system</a> (CMS). Our logic in selecting Mezzanine was twofold. One — Mezzanine is a CMS built using the Django framework. We use Django for our <a href="http://www.industrydive.com/industries/">other Dive sites</a>. Two — Mezzanine has native Bootstrap integration.</p>

<p>The rest of the story looks like this:</p> 

<figure>
	<img src="{{ site.url }}/media/img/dive-corporate.jpg">
</figure>

<p>Perhaps the site could benefit from another round of aesthetic enhancements – nothing is ever good enough for someone who cares about design, right?, and it’s certainly nowhere near as polished as the startup sites of <a href="http://www.f-d-n-y.com/">these gals and guys</a>, but we’re quite proud of it, nonetheless. We set out to create a responsive, corporate site in two months — on top of many other projects — and that’s what we did.</p>

<p>If this post helped you navigate past the, “Where do I start?” question, make my day and let me know! Questions, critiques, and anecdotes are also more than welcome. Find me <a href="https://twitter.com/rtmup">@RTMUP</a>.</p>


