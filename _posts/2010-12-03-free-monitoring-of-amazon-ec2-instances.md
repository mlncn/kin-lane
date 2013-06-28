---
layout: post
title: FREE Monitoring of Amazon EC2 Instances
url: http://kinlane.com/2010/12/03/free-monitoring-of-amazon-ec2-instances/
image: http://media.amazonwebservices.com/blog/cw_ec2_metrics.png
---
{% include JB/setup %}

     <a href="http://aws.amazon.com/cloudwatch/" target="_self">Amazon CloudWatch</a> has matured and now is available with a Freemium tier for monitoring your EC2 instance at no charge. <img src="http://media.amazonwebservices.com/blog/cw_ec2_metrics.png" alt="" width="250" align="right" /> Amazon Cloudwatch allows you to monitor:
</p>
<ul class="mainlist">
     <li>CPU Load
     </li>
     <li>Disk Input / Ouput
     </li>
     <li>Network Input / Output
     </li>
</ul>
<p>
     For your Amazon EC2 instances. The data is collected every five minutes and stored for two weeks. In true essence of a Freemium model you can then upgrade to a more detailed monitoring for .0015 / per hour per instance. If you are looking to take advantage of truly auto-scaling your Amazon EC2 infrastructure you need to start getting familiar with how Amazon CloudWatch works
</p>