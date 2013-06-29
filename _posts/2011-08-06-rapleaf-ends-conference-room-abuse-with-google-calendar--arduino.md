---
layout: post
title: Rapleaf Ends Conference Room Abuse with Google Calendar + Arduino
url: http://kinlane.com/2011/08/06/rapleaf-ends-conference-room-abuse-with-google-calendar-arduino/
image: http://kinlane-productions.s3.amazonaws.com/rapleaf-roominator.jpg
---
{% include JB/setup %}

Conference Room Abuse is where people 2 or more people randomly grab a conference without any regard to the schedule for the room. Its a problem many companies face.
To solve the problem <a title="Rapleaf designed the Roominator" href="http://blog.rapleaf.com/dev/2011/08/01/google-calendar-arduino-the-roominator/">Rapleaf designed the Roominator</a>, an open-source system of hardware and software that helps deal with conference room scheduling.
Bryan Duxbury of Rapleaf talks about what went into the Roominator:
<p>
     <em>The hardware consists of two parts: a display unit that's posted outside of each conference room, and a controller unit that's located in Rapleaf's wiring closet. The display unit shows the current and upcoming reservations and an LED status indicator that can tell you from a distance whether a room is good to grab. It also has a pair of buttons - one to make an ad-hoc reservation and one to cancel the current reservation. The controller unit interfaces with all the displays to distribute power and data, both of which run over a single standard Cat5e cable. Both the controller and the displays are Arduino-based.</em>
</p>
<p>
     <em>The software component is a Rails web site that allows for configuration and integrates with Google Calendar. Reservations made via Google Calendar are sync'd with the Roominator, and vice-versa. The controller unit polls the web site for the information it should pass to the displays.</em> The cool thing is its all open-source. You can build your own Roominator for your company. All the <a title="source code and schematics are on Github" href="https://github.com/bryanduxbury/roominator">source code and schematics are on Github</a>.
</p>