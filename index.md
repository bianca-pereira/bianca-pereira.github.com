---
layout: default
title: Home
---


<div class="container">
    <div class="row">
        <div class="col-md-8 text-center text-lg-left">
            <p>A researcher and software developer at work, a feminist by ideal, and a dancer and singer by passion. Welcome to my website!</p>

            <!-- Projects Index
			================================================== -->
			{% include list.html category="project" label="projects" %}


			<!-- Hobbies Index
			================================================== -->
			{% include list.html category="hobby" label="hobbies" %}
        </div>
        <div class="col-md-4 text-center text-lg-right">
            {% twitter https://twitter.com/bianca_oli_per limit=5 %}
        </div>
    </div>
</div>






