---
title:  "Example 2: Star Trek TV and Movies"
layout: base
---

# {{ page.title }}

This demonstrates a two column timeline. TV Series use a timespan, but movies only have one date, so they demonstrate timeline events used without a `from` specified.

{% include jekyll-timeline.html
   startYear=1966
   timelineHeight=2500
   
   col1Title="Star Trek TV"
   col1Events=site.data.starTrekTV
   
   col2Title="Star Trek Films"
   col2Events=site.data.starTrekFilms
%}