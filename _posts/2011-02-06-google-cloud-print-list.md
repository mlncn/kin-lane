---
layout: post
title: Google Cloud Print List
url: http://kinlane.com/2011/02/06/google-cloud-print-list/
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}

After authenticating using <a href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html" target="_blank">Google ClientLogin API</a>, you can request a list of your printers in their account:
The Google Cloud Print /list endpoint accepts the following parameter:

<ul>
     <li>
          <strong>proxy</strong> - Identification of the proxy, as submitted while registering the printer.
     </li>
</ul>
Here is an example JSON response: You can store the list of cloud printers in a database and / or display for the user to navigate and manage their Google Cloud Printers.
<h6 class="zemanta-related-title c2">
     Related articles
</h6>
<ul class="zemanta-article-ul">
     <li class="zemanta-article-ul-li">
          <a href="http://www.makeuseof.com/tag/print-phone-gmail-mobile-google-cloud-print/">How To Print From Your Phone With Gmail For Mobile &amp; Google Cloud Print</a> (makeuseof.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://www.kinlane.com/2011/02/introduction-to-google-cloud-print/">Introduction to Google Cloud Print</a> (kinlane.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://googlesystem.blogspot.com/2011/01/gmail-cloud-print.html">Gmail Cloud Print</a> (googlesystem.blogspot.com)
     </li>
</ul>