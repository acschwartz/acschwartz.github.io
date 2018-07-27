---
title: Contact
layout: page
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">

<center>
	<p>Thank you for taking the time to visit my page.<br>
	Let's connect!</p>

	<div class="social-links">
	    {% if site.email %}
	        <a class="link" data-title="{{ site.email }}" href="mailto:{{ site.email }}">
	            <i class="fas fa-envelope fa-2x icon-fa"></i>
	        </a>
	    {% endif %}

	    &nbsp;&nbsp;

	    {% if site.linkedin %}
	        <a class="link" data-title="linkedin.com/in/{{ site.linkedin }}" href="http://linkedin.com/in/{{ site.linkedin }}" target="_blank">
	            <i class="fab fa-linkedin fa-2x icon-fa"></i>
	        </a>
	    {% endif %}

	</div>
</center>
