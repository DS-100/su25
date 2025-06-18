---
layout: page
title: Staff
nav_order: 7
description: A listing of all the course staff members.
---

# Staff

## Course Staff Email

{: .important }
> Contact course staff **via Ed** with any questions or concerns. For sensitive matters, the staff email address [data100.instructors@berkeley.edu](mailto:data100.instructors@berkeley.edu) is monitored by the instructors and a few lead TAs.

<a name = 'inst'></a>

## Instructors

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' | sort: 'order' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

<a name = 'tas'></a>

## TAs

<div class="role">
  {% assign head_teaching_assistants = site.staffers | where: 'role', 'TA' %}
  {% for staffer in head_teaching_assistants %}
    {{ staffer }}
  {% endfor %}
</div>

<!-- <a name = 'ucs2s'></a>

## UCS2s

<div class="role">
  {% assign ucs2s = site.staffers | where: 'role', 'UCS2' %}
  {% for staffer in ucs2s %}
    {{ staffer }}
  {% endfor %}
     {% assign ucs2s = site.staffers | where: 'role', 'UCS2 (no form)' %}
  {% for staffer in ucs2s %}
    {{ staffer }}
  {% endfor %}
</div> -->

<a name = 'tutors'></a>

## Tutors

<div class="role">
  {% assign tutors = site.staffers | where: 'role', 'Tutor' %}
  {% for staffer in tutors %}
    {{ staffer }}
  {% endfor %}
    {% assign ucs1s = site.staffers | where: 'role', 'UCS1 (no form)' %}
  {% for staffer in ucs1s %}
    {{ staffer }}
  {% endfor %}
</div>