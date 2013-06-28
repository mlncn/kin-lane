---
layout: post
title: Moment - Scheduled Jobs API
url: http://kinlane.com/2011/01/29/moment-scheduled-jobs-api/
image: http://kinlane-productions.s3.amazonaws.com/moment-jobs-api.png
---
{% include JB/setup %}

     A big part of the web applications I build, is usually some sort of jobs management. Most functionality is triggered based upon user generated events. However there are many times where I need to schedule something as a job. I run most of my web applications on a Windows 2008 server, this is the platform I'm most familiar with. So I use the task scheduler built into the platform. <a href="http://momentapp.com/" target="_blank"><img class="c1" src="http://kinlane-productions.s3.amazonaws.com/moment-jobs-api.png" alt="" align="right" /></a> When I migrate applications off my native development environment I need a better way to trigger scheduled jobs. I found <a href="http://momentapp.com/" target="_blank">Moment</a>, a Software as a Service (SaaS) for scheduling jobs. They provide a simple <a href="http://momentapp.com/" target="_blank">RESTful API for scheduling HTTP based jobs</a> you need to run. I tend to just create my jobs as simple <a href="http://www.kinlane.com/category/php/">PHP</a> scripts and expose them at a non-indexed public URL. So Moment is a great solution. Its good to see useful utility APIs that everyone can use, doing one thing, and doing it well!
</p>