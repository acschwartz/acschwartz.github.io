---
title: Résumé
layout: page
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">

<p>
Hey Annie, you need to add "Education", "Skills", etc! ;)
</p>


<h2>Work Experience</h2>
<div class="jobs-table text-normal">
	{% for job in site.data.jobs %}
		<div class="row">
		    <div class="col job-title strong">
			    {{ job.title }}
		    </div>
		    <div class="col job-date">
				{% if job.start-year == job.end-year %}
					{{ job.start-year }}
				{% else %}
					{{ job.start-year }} &ndash; {{ job.end-year }}
				{% endif %}
		    </div>
		</div>

		<div class="row">
		    <div class="col job-employer">
		    	{{ job.employer}}
		    </div>
		</div>

		<div class="row">
		    <div class="col job-description">
		    	{{ job.description }}

		    	{% if job.duties %}
		    		<ul>
		    			{% for duty in job.duties %}
		    				<li>{{ duty }}</li>
		    			{% endfor %}
		    		</ul>
		    	{% endif %}
		    </div>
		</div>
	{% endfor %}
</div>


<h2>Skills</h2>	
<ul class="skill-list">
	<li>HTML - Jade - Haml - Erb</li>
	<li>Responsive (Mobile First)</li>
	<li>CSS (Stylus, Sass, Less)</li>
	<li>Css Frameworks (Bootstrap, Foundation)</li>
	<li>Javascript (Design Patterns, Testes)</li>
	<li>NodeJS</li>
	<li>AngularJS - ReactJS</li>
	<li>Grunt - Gulp - Yeoman</li>
	<li>Git</li>
	<li>PHP</li>
	<li>Python</li>
	<li>MySQL - MongoDB</li>
	<li>Scrum and Kanban</li>
	<li>TDD e Continuous Integration</li>
</ul>


