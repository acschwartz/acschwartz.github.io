---
title: Contact
layout: page
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">


A contact page that includes various ways for employers to get in touch with you. You can include any methods of communication (phone number, email, social media, etc.) that you’re comfortable with, <b>but I do require that you provide a link to your LinkedIn profile</b>.

<center>
	<p>Let's connect!</p>

	<div class="social-links">
	    {% if site.email %}
	        <a class="link" data-title="{{ site.email }}" href="mailto:{{ site.email }}">
	            <i class="fas fa-envelope fa2x"></i>
	        </a>
	    {% endif %}

	    {% if site.linkedin %}
	        <a class="link" data-title="linkedin.com/in/{{ site.linkedin }}" href="http://linkedin.com/in/{{ site.linkedin }}" target="_blank">
	            <i class="fab fa-linkedin fa2x"></i>
	        </a>
	    {% endif %}

	</div>
</center>