---
layout: default
title: CV
description: Ollie's Curriculum Vitae
categories: none
noindex: true
---

<p class="centered">
  First Class Theoretical Physics MSci with technical mindset and entrepreneurial streak.
</p>

## Experience

### Technical&nbsp;Consultant / HP&nbsp;Autonomy / 2012&nbsp;-&nbsp;2014

#### A client-facing post-sales consultant providing customisation and delivery of enterprise software.

- Development of extensive customised logic for banks' post-trade documentation management, requiring a highly-performant and failure-resistant Java/J2EE application. Also controlled server configuration and integration with upstream systems. Extensive front-end design using modern technologies while ensuring back-compatibility with client's legacy browsers.

- Helped develop new software offering for HP, following requirement capturing from a law enforcement agency. Integrated third-party facial-recognition software and a heavily tailored HTML/CSS/JavaScript interface into a pre-existing content management offering.

- Joined several high-pressure projects, visiting clients to manage expectations while liasing with Engineering and Support teams to effectively resolve product issues. Restored positive relationships through flexibility and willingness to assist wherever possible (as was reflected by very positive feedback from clients post go-live).

- Worked with several highly experienced external Java consultants to gain substantial "best-practice" knowledge of development. Inherited responsibility after their contracts ended.

- Created and shared time-saving scripts/tools for automating builds and deployments during off-site development, as well as proposing project tracking and collaboration tools to management which were subsequently adopted.

- Oversaw critical migrations and go-live events (often outside the UK, and outside working hours), reacting fast to issues and identifying resolutions or workarounds in the absence of support.

### Master's&nbsp;Dissertation / University&nbsp;of&nbsp;Nottingham / 2011

#### Quantum Reflection of Ultra-Cold Atoms from Room Temperature Silicon

This project involved computationally analysing quantum mechanical phenomena, through modelling the reflection of ultra-cold groups of atom as they approached a surface. I repeatedly improved the methods implemented in MATLAB and C++, such that more accurate representations could be made. The resulting project was "one of the best" the supervisor had seen.

## Personal Projects

{% assign projects = site.projects | reverse %}
{% for project in projects %}
  <p>
    <a href="{{ project.url }}">{{ project.title }}</a>
    -
    {{ project.summary }}
    {% if project.website %}
      <a href="{{ project.website }}">
        {{ project.website_pretty }}
      </a>
    {% endif %}
  </p>
{% endfor %}

## Education

MSci Hons University of Nottingham (First&nbsp;Class) in Physics with Theoretical Physics (2007-11)

A-levels: Maths&nbsp;(A), Physics&nbsp;(B) and Chemistry&nbsp;(B) and AS&nbsp;Economics&nbsp;(B)

## Skills Profile

### Problem Solving / Analytical Skills

Enjoy programming-based problem solving such as
<a class="printable" href="http://projecteuler.net/">Project Euler</a>
or
<a class="printable" href="http://pythonchallenge.com/">Python Challenge</a>.

Technical reviewer for several programming books focussing on Node.js and Test Driven Development.

### Leadership

President of Nottingham University Physics Society - Responsible for managing 12-person committee.

Exceptional leadership and organisational skills led to additional responsibilities and promotion from steward to supervisor, as part of my duties with the Oxfam Festival Stewarding organisation.

### Communication

Assessed and delivered appropriate level of information to HP and client management teams.

Developed my communication skills significantly while travelling worldwide independently for six months.

<!--
Fielded phone calls and emails in response to a multitude of issues as a Volunteer for Nottingham University Nightline - a listening, emotional support and information service run by students for students.
-->

### Teamwork

Working as part of HP consulting teams to deliver projects on schedule and within budget.

As a festival steward supervisor for Oxfam, I delegated tasks, made quick decisions, and managed and supported a team of 10-15 volunteers.

On Duke of Edinburgh expeditions, worked with the team to navigate and achieve goals.

Sailed dinghies recreationally and as part of the school racing team. Effective teamwork allowed quick response to changing conditions and the tactics of others.

### Other

Earned Nottingham Advantage Award (a university-endorsed acknowledgement of proactive approaches to the development of student skills) through completing a varied series of presentations, workshops and team building exercises.

- Outreach work for physics department open days.
- Full, clean UK driving license held for 8 years.
- Independent travel in Asia, Australasia and Europe.

## Technical Competencies

<div class="skill-set">
  {% for competency in site.data.competencies %}
    {% case competency.level %}
    {% when "expert" %}
      <span class="skill skill-expert"><i class="fa fa-star"></i> {{ competency.name }}</span>
    {% when "intermediate" %}
      <span class="skill skill-intermediate"><i class="fa fa-star-half-full"></i> {{ competency.name }}</span>
    {% else %}
      <span class="skill skill-beginner"><i class="fa fa-star-o"></i> {{ competency.name }}</span>
    {% endcase %}
  {% endfor %}
</div>

## Other Interests

Sailing /
Kayaking /
Travelling /
Volunteering /
Cycling /
Home Automation /
Snowboarding /
Dvorak Keyboard
