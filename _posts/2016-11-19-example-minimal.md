---
title:  "Example 1: Minimal Configuration"
layout: base

exampleEvents:

- name: 2015 until now
  from: 2015-01-01
  to: now # "now" is the only supported non-date keyword
  description: A test event, running from `2014-01-01` until `now`

- name: Another Event
  from: 2013-06-01
  to: 2014-09-11
  description: This event exactly abuts the next one

- name: Oldest Event
  from: 2010-06-10
  to: 2013-05-01 # months are inclusive, so running to 2013-05 will exactly meet the next event that starts at 2013-06

---

# {{ page.title }}

A minimal configuration example.

{% include jekyll-timeline.html
   startYear=2010
   timelineHeight=600
   col1Title="Column Title"
   col1Events=page.exampleEvents
%}
