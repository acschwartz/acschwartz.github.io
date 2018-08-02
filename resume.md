---
title: Résumé
layout: page
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">

<p>
I am currently searching for a fully remote internship. Below are my résumés for two internship postings that offer remote work. Since I have previously worked as part of a remote team, I included this in both résumés.
</p>


{% for resume in site.data.resumes %}
<h4 style="
    margin-bottom: 0;
"><div class="social-links" style="display: inline;padding-left: .33em;"> <a href="{{site.url}}/{{resume.resume-path}}" target="_blank" class="link" data-title="View PDF" style="
    width: unset;
    /* height: unset; */
    height: 33px;
"> <i class="icon-fa fas fa-file-pdf fa-2x red" style="
    padding-right: .15em;
    vertical-align: middle;
    font-size: 2.5rem;
"></i><span class="icon-fa"> <!-- <= this is just straight up messy over here lol needed to get this done -->
Version {{ forloop.index }} - {{ resume.position }} at {{ resume.employer }}</span></a> </div></h4>
<p style="margin-left: 2em;margin-top: 0; font-style:italic">{{ resume.description }} </p>
{% endfor %}


<!-- <h2>
	Web Developer Intern
	<div class="social-links" style="
	    display: inline;
	    padding-left: .33em;
	">
		<a href="file.pdf" class="social-links link" data-title="View PDF">
			<i class="icon-fa fas fa-file-download fa-lg"></i>
		</a>
	</div>
</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</p>

<h2>C# Developer Intern</h2>
<div class="social-links text-normal" style="
    margin: 0;
    margin-left: 1.5rem;
">    
	<a href="file.pdf" class="social-links link" data-title="Download PDF" target="_blank" style="
    font-weight: normal;
    height: unset;
    width: unset;
	">
		<i class="icon-fa fas fa-file-pdf fa-lg" style="
    	margin-right: .3rem;
    	/* font-size: 3rem; */
		"></i>
		View Résumé
	</a>
	<br>
	<a href="http://indeed.com" class="social-links link" data-title="External Link" target="_blank" style="
    font-weight: normal;
    height: unset;
    width: unset;
	">
		<i class="icon-fa fas fa-link fa-md"></i>
		Job Posting
	</a>
</div>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</p> -->

