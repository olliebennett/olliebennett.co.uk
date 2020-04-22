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

- Variety of on-site implementation projects for banks across Europe.
- Worked on critical document-processing systems, learning from highly skilled Java/J2EE developers.
- Developed interface for new software offering, integrating facial recognition software following requirement gathering from law enforcement agency.
- Took initiative to create time-saving tools for automating builds and deployments.
- Sent in to resolve derailed high-pressure projects and restore client relationship.
- Oversaw critical migrations and go-live events (abroad and outside working hours), resolving issues or workarounds in the absence of support.

### Master's&nbsp;Dissertation / University&nbsp;of&nbsp;Nottingham / 2011

#### Quantum Reflection of Ultra-Cold Atoms from Room Temperature Silicon

- Computational analysis of quantum mechanical phenomena, modelling reflection of Bose-Einstein condensates as they approach a surface.
- Repeatedly improved performance in MATLAB and C++ to improve models.
- Resulting project was "one of the best" the supervisor had seen.

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
