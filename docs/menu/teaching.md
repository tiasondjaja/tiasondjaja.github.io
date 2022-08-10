---
layout: page
title: Teaching
permalink: /teaching
---



#### Selected Teaching Modules
{% for module in site.teachingmodules %}
{% if module.status != 'draft' %}
+ [ **{{ module.name }}** ]( {{ module.url }}) &nbsp; <span style="color:#2B547E">[{{ module.tag | downcase}}]</span>

	{{module.short_description}}

{% endif %}
{% endfor %}


#### Previous Teaching Experiences

##### At New York University
+ CORE-UA.111: Quantitative Reasoning: From Data to Discovery
+ CORE-UA.107: Quantitative Reasoning: Probability, Statistics, and Decision-Making
+ CORE-UA.110: Quantitative Reasoning: Great Ideas in Mathematics
+ MATH-UA.009: Algebra and Calculus
+ MATH-UA.120: Discrete Mathematics
+ MATH-UA.121-123: Calculus 1-3
+ MATH-UA.140: Linear Algebra
+ MATH-UA.211: Math for Economics 1
+ MATH-GA.2840-004: Written and Oral Presentation (co-taught with Aleks Donev in Spring 2018)
+ MATH-UA.998: Independent Study (Introduction to Linear and Convex Optimization)
+ CSCI-UA.520-521: Undergraduate Research

##### At Cornell University
+ ORIE 3310/5310/5311: Optimization 2 (Instructor)
+ Cornell University Prison Education Program, Auburn Correctional Facility: Algebra (Instructor)
+ ORIE 4580/5580: Simulation Modeling and Analysis (Teaching Assistant)
+ ORIE 4350: Introduction to Game Theory (Teaching Assistant)
+ ORIE 3300/5300: Optimization 1 (Teaching Assistant)
+ ORIE 3310/5310/5311: Optimization 2 (Teaching Assistant)

##### Other Teaching and Outreach
+ Summer Program for Young Scholars, Center for Mathematical Talent, NYU
+ GSTEM Summer Program, NYU
+ Expanding Your Horizons, Cornell University
