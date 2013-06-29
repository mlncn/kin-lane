---
layout: post
title: Quora Exposes JSON API
url: http://kinlane.com/2011/01/07/2497/
image: http://kinlane-productions.s3.amazonaws.com/quora-logo.jpg
---
{% include JB/setup %}

To request particular fields about the currently logged-in user, you can add fields to a query string and append to <a href="Quora%20Exposes%20JSON%20API" target="_blank">http://api.quora.com/api/logged_in_user</a>.
Currently supported fields include: <img src="http://kinlane-productions.s3.amazonaws.com/quora-logo.jpg"  width="200" align="right" />
<ul>
     <li>Inbox
     </li>
     <li>Followers
     </li>
     <li>Following
     </li>
     <li>Notifs
     </li>
</ul>Here is an example call: <a href="http://api.quora.com/api/logged_in_user?fields=inbox,notifs">http://api.quora.com/api/logged_in_user?fields=inbox,notifs</a>
This will return Inbox and Notification related information for the authenticated user.
This is not a full-blown API release by Quora. Quora engineer Edmond Lau posted information on Quora about the API, stating that it is in its alpha stage and is only meant to support existing <a href="http://www.quora.com/Is-anyone-working-on-a-Quora-Chrome-extension" target="_blank">Quora Chrome</a> and <a href="http://www.quora.com/Is-anyone-working-on-a-Quora-Chrome-extension" target="_blank">Quora Firefox extensions</a>.
Even though it doesn't have all the supporting elements of an official API release, the fact that the Q&amp;A startup has established <a href="http://api.quora.com/">api.quora.com</a> for its use, indicates that it plans to invest more energy around an official <a href="http://www.quora.com/Edmond-Lau/Quora-Extension-API" target="_blank">Quora API</a>.