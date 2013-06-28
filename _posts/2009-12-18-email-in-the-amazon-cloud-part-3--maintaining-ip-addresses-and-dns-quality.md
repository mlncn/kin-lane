---
layout: post
title: Email in the Amazon Cloud Part 3 - Maintaining IP Addresses and DNS Quality
url: http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}

     Sending large amounts of email and ensuring they get received requires a lot of work and you need to make sure your mail framework is setup correctly and is healthy. This takes a lot of work and maintenance. First off I reserve 11 <a class="zem_slink" title="IP address" rel="wikipedia" href="http://en.wikipedia.org/wiki/IP_address">IP addresses</a> with <a href="http://aws.amazon.com/">Amazon Web Services</a>. I reserve these 11 IP addresses and never let them back into the general pool. I setup <a class="zem_slink" title="Domain Name System" rel="wikipedia" href="http://en.wikipedia.org/wiki/Domain_Name_System">DNS</a> for my domain to reflect using 10 of the IP addresses as smtp1.mydomain.com through smtp10.mydomain.com and properly setup <a class="zem_slink" title="MX record" rel="wikipedia" href="http://en.wikipedia.org/wiki/MX_record">MX records</a> accordingly. Now <a class="zem_slink" title="Reverse DNS lookup" rel="wikipedia" href="http://en.wikipedia.org/wiki/Reverse_DNS_lookup">reverse DNS</a> on IP addresses is nice, but in my experience is not mission critical for sending email. All last year we were fine, I sent probably 10-20 large email blasts using this setup, with no major problems with emails being received. Before doing any emailing I check all my IP addresses against major blacklists to see if we've been listed. We have been listed on blacklists before and easily was able to get removed with no problem. Then in November we encountered <a href="http://www.kinlane.com/?p=1102">Trend Micro MAPS</a>.
</p>
<p class="c1">
     <strong>Email in the Amazon Cloud</strong> - <a href="../?p=1095">Part 1</a> - <a href="../?p=1098">Part 2</a> - <a href="../?p=1100">Part 3</a> - <a href="../?p=1102">Part 4</a> - <a href="../?p=1104">Part 5</a> - <a href="../?p=1106">Part 6</a> - <a href="../2010/07/email-infrastructure-in-the-amazon-cloud/">Guide to Email in the Amazon Cloud</a>
</p>