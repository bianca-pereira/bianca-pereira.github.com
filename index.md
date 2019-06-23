---
layout: default
title: Home
---


<div class="container">
    <div class="row">
        <div class="col-md-9 text-center text-lg-left">
            <p>A researcher and software developer at work, a feminist by ideal, and a dancer and singer by passion. Welcome to my website!</p>

            <!-- Recent posts Index
            ================================================== -->
            {% include list.html category="all" label="Recent Posts" limit=3 %}

            <!-- Projects Index
			================================================== -->
			{% include list.html category="project" label="Projects" limit=3 %}


			<!-- Hobbies Index
			================================================== -->
			{% include list.html category="hobby" label="Hobbies" limit=3 %}
        </div>
        <div class="col-md-3 text-center text-lg-right">
            {% twitter https://twitter.com/bianca_oli_per limit=5 %}
        </div>
    </div>
</div>






