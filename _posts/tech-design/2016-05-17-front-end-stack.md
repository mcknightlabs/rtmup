---
layout: article
title: Front-end stack breakdown 
description:
category: tech
tags: 
- design
- tech
---

<p>As Industry Dive matures, I want to make sure we have a formal set of guidelines for front-end design.</p>

<p><em>Quick aside – I'm a huge proponent of the full-stack approach to digital product design. I look for and <a href="http://industrydive.com/jobs/">hire designers</a> who can go from pen and paper mockup all the way through the front-end process. There will be no handing off of Photoshop templates to devs as long as I'm at ID.</em></p>

<p>Standardization of front-end tools and techniques is important for so many reasons: ensuring code readability and maintainability, improving efficiency of team collaboration, quickly bringing new designers up-to-speed, keeping build-time to a minimum, reducing code bloat and increasing site speed, etc.</p>

<p>The rest of this post details the front-end stack I defined for our team, including my rationale for selecting particular tools. After providing an overview of the stack, I cover how I built a standards-first environment for our front-end designers to quickly spin up and start working on projects.</p>

<h2>Project Goals</h2>
<p>When I set out to more formally define our stack, I gave myself the following project objectives:</p>
<ul>
	<li>Keep # of tools and amount of code to a minimum.</li>
	<li>Don't acrue technological debt due to frameworks. Must be easy to switch to new tools without rebuilding entire sites.</li>
	<li>Create a simple system that new front-end designers can learn in a few days.</li>
</ul>

<h2>Front-end Stack</h2>

<h3>Code Editor</h3>
<p><a href="https://www.sublimetext.com/">Sublime</a></p>

<p><a href="https://generalassemb.ly/blog/sublime-text-3-tips-tricks-shortcuts/">Shortcuts and tips</a></p>

<h3>Version Control System</h3>
<p><a href="https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control">Git</a> + <a href="https://github.com/">Github</a></p>

<p><a href="https://git-scm.com/book/en/v2/Getting-Started-Git-Basics">Intro to Git</a> | <a href="https://guides.github.com/activities/hello-world/">Intro to Github</a></p>

<h3>CSS Reset / Normalize</h3>
<p><a href="https://necolas.github.io/normalize.css/">Normalize</a></p>
<p>A CSS Reset, like <a href="http://meyerweb.com/eric/tools/css/reset/">Eric Meyer's</a>, completely removes default browser styling. Normalize standardizes default browser styling. I decided to go with Normalize to avoid rewriting a lot of standard CSS – e.g. for bulleted lists, forms, etc.</p>

<h3>CSS Pre-Processor</h3>
<p><a href="http://sass-lang.com/">SCSS</a></p>

<p><a href="https://www.sitepoint.com/8-tips-help-get-best-sass/">Usage tips</a> | <a href="http://alistapart.com/article/dry-ing-out-your-sass-mixins">Keep it "DRY"</a></p>

<h3>CSS Framework</h3>
<p>Custom + <a href="http://susy.oddbird.net/">Susy</a></p>

<h4>Susy</h4>
<p>For several years, I used parts of the Foundation front-end framework for Industry Dive web app projects. Eventually, I found that our team was only using the responsive grid. To simplify our build process and front-end stack, I decided to explore other options.</p>

<p>The problems I wanted to solve by switching were as follows: 1) Reduce the overall code base 2) Make it easier for a front-end designer to spin up a new project / reduce setup time and 3) Further <a href="https://medium.com/@pstonier/using-bourbon-neat-for-css-grid-structure-with-semantic-markup-cd1b13d48dc1#.r63gtcx3y">separate content from presentation</a> – e.g. get rid of "row," "column," and other presentation classes that appear in the HTML.</p>

<p>Our solution was a custom SCSS sheet + Susy, a framework to help build responsive grids with SASS.</p>
<p>I opted not to use <a href="http://neat.bourbon.io/">Neat</a>, because it's more of a grid "system" – you are including all of the styles for all of the grid sizes, even ones that don't appear in your project. With Susy, you're only adding the grid styles that will appear in your project. Read more about Susy vs Neat <a href="https://www.sitepoint.com/sass-grids-neat-susy/">here</a>.</p>

<h4>Custom SCSS</h4>
<p>The custom framework I developed is divided into 5 parts:</p>
<ol>
	<li>Normalize – to "normalize" CSS across browsers</li>
	<li>Variables and extends – for commonly repeated properties</li>
	<li>Mixins – for Rem font-size, breakpoints, transitions, etc.</li>
	<li>Universal – global CSS for things like anchors, headers, and buttons</li>
	<li>Page-specific</li>
</ol>

<p>Additional stylesheets include:</p>
<ul>
	<li>ie.css</li>
	<li>print.css</li>
</ul>

<p>Integrated into the custom framework is Susy.</p>

<h3>Templating</h3>
<p><a href="https://www.djangoproject.com/">Django</a> and <a href="https://jekyllrb.com/">Jekyll</a></p>
<p>Industry Dive uses Django, a python-based web framework, for its various web apps – e.g. publication sites, landing pages, etc. For smaller static sites like Industrydive.com/brandstudio, we sometimes use Jekyll.</p>

<p><a href="https://www.djangoproject.com/start/">Intro to Django</a> | <a href="https://jekyllrb.com/docs/quickstart/">Intro to Jekyll</a></p>

<h3>JS Core Libraries</h3>
<p><a href="">jQuery</a></p>

<p>jQuery enables you to more easily craft JS for DOM manipulation, event handling, animations, etc. <a href="https://www.udacity.com/course/intro-to-jquery--ud245">Udacity intro to jQuery</a></p>

<h3>Package Manager</h3>
<p><a href="https://www.npmjs.com/">npm</a></p>
<p>npm enables you to download and manage JS packages for projects and manage dependencies. <a href="https://docs.npmjs.com/getting-started/what-is-npm">Intro to npm</a></p>

<p><a href="http://bower.io/">bower</a></p>
<p>Bower helps you manage your front-end packages. It searches for and downloads updates to jQuery, Angular, etc. <a href="https://www.codementor.io/bower/tutorial/beginner-tutorial-getting-started-bower-package-manager">Intro to bower</a></p>

<h3>Build System</h3>
<p>We use <a href="">npm</a> scripts, instead of Grunt or Gulp. <a href="https://css-tricks.com/why-npm-scripts/">Intro to npm</a> | <a href="https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.swq5mrla8">Why npm vs Grunt or Gulp</a></p>

<h3>Polyfills</h3>
<p><a href="https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills">Modernizer</a> and <a href="https://github.com/chuckcarpenter/REM-unit-polyfill">REM unit polyfill</a></p>

<h2>Front-end Design Environment</h2>

<p>To make it dead simple for our designers to set up front-end projects that rely on a consistent set of tools and techniques, I created a zip file containing a "standards-first" design environment. I call it "standards-first," because the environment contains the latest description of our stack, links to our CSS/HTML/JS/Git styleguides, and a "living" styleguide for easy access to reusable code.</p>

<h3>What's inside the zip file:</h3>

<h4>Read.me</h4>
<ul>
	<li>A description of the Dive front-end stack (similar to this post)</li>
	<li>Instructions on how to configure our front-end design environment – e.g. how to install package managers, etc.</li>
	<li>Links to Dive's CSS/HTML/JS/Git styleguides</li>
	<li>Link to Dive's "living" style guide</li>
</ul>

<h4>Directory structure</h4>
<ul>
	<li>css > app.min.css, ie.css</li>
	<li>scss > app.scss (Normalize + Susy grid)</li>
	<li>js > jquery.min.js, modernizer.js, rem-polyfill.js</li>
	<li>img</li>
	<li>index.html (boilerplate)</li>
</ul>

<!--<p>I figured this package might be useful to other front-end designers and devs, so I decided to create a more generic version and make it open source.</p>

<button class="button">Download front-end package</button>-->

<h3>Resources:</h3>
<ul>
	<li><a href="http://coderesponsibly.org/">Front-end best practices</a></li>
	<li><a href="https://www.smashingmagazine.com/2015/07/smarter-grids-with-sass-and-susy/Why">Why Susy + custom SCSS over a framework like Bootstrap or Foundation</a></li>
	<li><a href="https://medium.com/@rogerdudler/front-end-technology-stack-survey-2014-809f7a8c92f3#.xnzcpscga">What do other devs front-end stacks look like?</a></li>
</ul>


