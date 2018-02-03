---
layout: article
title: How I design digital media products
description: This is a snapshot of my workflow.
category: tech
tags: 
- design
- tech
---

<p>Users matter. Clients matter. ...It can be quite difficult to design with multiple stakeholders top of mind. When balancing varied, and sometimes competing, interests, a designer faces seemingly intractable problems at every corner. How do I integrate this sponsor logo on our editorial project without the readers assuming that our content was created by the sponsor? How can I integrate client messages (ads) on our sites in ways that are, as much as possible, valued by our readers?</p>

<p>There are rarely easy answers to questions like these. They take a ton of experimentation and sometimes a bit of statistical testing. The complexity of these type of problems also points to the core value that I provide; I know how to use design principles to strategically address business problems.</p>

<p>Given that I want to dedicate as much time as possible to leveraging this core value, I see it as an imperative to have a design process that's as efficient and flexible as possible.</p>

<p>What does my process look like? It's a moving target. I'm constantly refining it. But I can give you a rough outline. What follows is generally how I approach the creation of new features for – and even entire redesigns of – existing web apps.</p>

<h3>Step 1: Define specific problems and goals</h3>
<p>This is how I begin most all design projects. Understanding the problems and goals enables you to craft a clear roadmap to success and figure out which tools and approaches are likely to prove most effective. Even at this early stage, I'll go ahead and set up a project timeline with tentative deadlines and schedule a few check-in meetings with stakeholders. It's important to keep momentum moving forward and constantly measure progress.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/goals.jpg" class="img-border">

<h3>Step 2: Gather relevant user data</h3>
<p>The user data that guides my design comes from a lot of different sources: heat maps, click maps, Google Analytics, video recordings of user sessions, user surveys, user interviews, etc. Which data sets I employ is largely dependent upon project goals.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/survey.jpg" class="img-border">

<h3>Step 3: Conduct competitive analysis</h3>
<p>Although I work for a B2B media pub, I always cast my net into the B2C pool, too. A lot of B2B design is just awful and not worth analyzing.</p>
<p>I often start off by looking for elements on other sites that are similar in functionality to what I am creating. If I'm working on a new desktop homepage layout for Industry Dive's news sites, I will pour over the similar pages on pubs like WaPo, NYT, FiveThirtyEight, Vice, SyriaDeeply, etc. I try to understand their information architecture, color strategy, font-pairing logic, etc.</p>

<p>I usually screenshot a lot when conducting a competitive analysis and save the images in a folder for later reference. Occasionally, I'll even compare particular sites and elements against a set list of criteria in a spreadsheet to search for commonalities. I want to know what our users – business executives – are experiencing on other sites.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/comp_analysis.jpg" class="img-border">

<h3>Step 4: Come up with a plan of attack.</h3>

<p>Often, this is a bulleted list that I save as an email message. It's for my personal reference. For larger projects, I might create a slide deck compiling all of the user testing data, feedback, competitive analysis, and a lit review of best practices. All of this data is mapped back to the specific project goals with "actionable insights" called out.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/slide_deck.jpg" class="img-border">

<h3>Step 5: Sketch pen and paper mockups (for myself)</h3>
<p>I generally don't spend a lot of time sketching. I use this technique mostly for information architecture purposes – to figure out the hierarchy of content and quickly explore UI and UX elements. After I have a few basic notes, I jump into Keynote or Sublime.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/sketch-demographics.jpg">

<h3>Step 6: Create high-fidelity mockups in Keynote or code</h3>
<p>I am not a fan of using Photoshop to create pixel-perfect mockups. It's a huge time suck and can drag down a project. That said, it's nice to have some sort of high-fidelity representation of the UI for team members and users to review.</p>
<p>That's where a tool like Keynote comes in. In only a couple of hours, I can go from a blank canvas to a beautiful, animated mockup. The best part is that I can explore all sorts of interactivity – e.g. the navigation UX. I learned about this technique a few years ago while reading the <a href="https://library.gv.com/the-product-design-sprint-prototype-day-4-ebab764ac69f#.vo8zzk25d">Google Ventures blog</a>.</p>

<p>The video below, exported from Keynote, is a mockup I created while designing the main menu navigation for Industry Dive's news publications.</p>

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://player.vimeo.com/video/155146496' frameborder='0' webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe></div>

<h3>Step 7: Conduct X rounds of design review + user testing + iteration</h3>
<p>As I mock up designs in Keynote or as static HTML/CSS/JS files, I make an effort to conduct continual user testing.</p>

<p>If I want to test whether or not the new mobile navigation is intuitive, I'll grab both coworkers and real users and ask them to find specific parts of the web app. E.g. Find a topic you care about. Find the contact form. Find where you can sign up for the email newsletter. I then observe and document what unfolds. This type of user input is invaluable and easy to gather. Testing with as few as <a href="https://www.nngroup.com/articles/why-you-only-need-to-test-with-5-users/">5 users</a> can help you identify a lot of the most obvious UX issues.</p>

<p>After creating user-tested mockups, I lead review sessions with the project stakeholders. These meetings focus on how the design directly addresses project goals. Feedback gets explored on the whiteboard and finally noted in an email that will be sent to the participants. For larger projects, I also post all design mockups and stakeholder feedback into project management software like Basecamp. It's a great way for everyone to revisit old mockups and view all relevant feedback. Sure beats trying to keep track of email threads!</p>

<p>Also on larger projects, the "review/iterate" step is repeated multiple times. Design > review + user testing > iterate > review + user testing > etc.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/review.jpg" class="img-border">

<h3>Step 8: Code the front-end</h3>
<p>Over the years, I've noticed that web design has some striking similarities to filmmaking. One that always jumps to mind is how the work of art changes at each step in the process. A film, for instance, is made once when written, remade when shot, then remade again when it's edited. Similarly, the digital products I help create are made once with pen and paper, remade in Keynote, then remade again in code after user testing. At each step, the art usually changes in fundamental ways.</p>
<p>On to the technical details... I check out a new branch on the Github repo and start making changes. Version control is a must when working with code.</p>
<p>At Industry Dive, this often means I'm working with a SASS install of Foundation. Front-end frameworks like Foundation and preprocessors like SASS are awesome. Such time savers. To make the build process even more efficient, I configure a JS task runner like Grunt. JS task runners takes care of repetitive tasks like generating responsive images, adding vendor prefixes, etc.</p>
<p>Integrated with the static HTML/CSS/JS is the web framework – Django at Industry Dive. Using the Django docs, I template the feature or pages and prepare to hand everything off to the tech team.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/sublime.jpg">

<h3>Step 9: Walk tech team through required server side issues</h3>
<p>After templating features or entire pages in Django, I walk the tech team through the changes. This way they can note the specific python views and models they will need to create and/or refactor. All of these mini-projects then become Github issues.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/django.jpg" class="img-border">

<h3>Step 10: Browser test</h3>
<p>Oh how I hate thee, IE. In all seriousness, you need to support the browsers your users are using. For Industry Dive, that meant we supported IE7 until 2015. Now, we support back to IE8. "Support" means that we ensure the site is navigable and the content accessible.</p>
<p>Thankfully there are some great pollyfills out there for things like media queries and REMs.</p>
<p>To check out how a site looks and functions in IE, I usually use VirtualBox. Screenshots from an online browser tester won't suffice. You actually need to test how a real user would interact on your site. Does the dropdown menu open when you click it in IE8? A browser screenshot can't answer that.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/ie8_topic_page.jpg">

<h3>Step 11: Launch</h3>
<p>This is the stage at which I start making Github issues for progressive enhancements and new issues noted by users and team members.</p>

<img src="{{ site.github.url }}/media/img/tech-design/2016-02-09-design-process/corp_site.jpg" class="img-border">
