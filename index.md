---
layout: page
title: Home
nav_order: 1
description: >-
    Data Science for Economists, UC Berkeley, Spring 2023
---

# Data Science for Economists
{: .mb-2 }
UC Berkeley, Spring 2023
{: .mb-2 .fs-6 .text-grey-dk-000 }

{: .mb-2 }
**Instructor:** Eric Van Dusen (<a>ericvd@berkeley.edu</a>)
{: .mb-0 .fs-5 .text-grey-dk-000 }

{: .mb-3 }
**Lecture:** MWF 1PM-2PM, **Office Hours:** See [Ed](https://edstem.org/us/courses/34369/discussion/)
{: .mb-0 .fs-5 .text-grey-dk-000 }

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

<!-- [Zoom links](https://edstem.org/us/courses/25130/discussion/2076738){: .btn .btn-purple }  -->
[Lecture recordings](https://kaltura.berkeley.edu/){: .btn .btn-blue }

+ <span style="color:red">**The class website is being built at the moment.** </span>
+ The schedule and dates listed below are tentative and may be subject to change. 
+ All announcements are on [Ed](https://edstem.org/us/courses/34369/discussion/). Make sure you are enrolled and active there.
+ The [Syllabus](../syllabus) contains a detailed explanation of how each course component will work this semester
+ If you plan to add late, make sure you contact the staff first to see if you can make up the missed assignments before officially adding the class. 

<br>

{% for module in site.modules %}
{{ module }}
{% endfor %}
