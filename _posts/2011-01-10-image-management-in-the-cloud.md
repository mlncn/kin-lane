---
layout: post
title: Image Management in the Cloud
url: http://kinlane.com/2011/01/10/2517/
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}

I store all my images centrally at <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a>. This may not be an ideal solution for everyone, but it works for me. Its a complete storage area for all my images, audio, video and other documents.
I use a combination of <a href="https://console.aws.amazon.com" target="_blank">Amazon Console</a>, <a href="https://addons.mozilla.org/en-US/firefox/addon/3247/" target="_blank">S3Fox for Firefox</a>, <a href="http://cyberduck.ch/" target="_blank">Cyberduck</a> and <a href="https://www.jungledisk.com/" target="_blank">Jungle Disk</a> to manage my Amazon S3 files. No time to explain the madness, it just works.
I have a central bucket at Amazon S3 for storing ALL images I need to support my public online properties. I have set a bucket policy for this bucket enforcing that all objects within are automatically publicly available. This saves me time in having to set the ACL for each object.
When I have a screenshot or creative commons image that I have found that I need to use in my blog I download, crop, resize, download and rename. Then I immediately upload to my Amazon S3 public bucket, and then copy the location to my clipboard.
With the URL of the image on Amazon S3 I go back to Wordpress and paste the URL in my blog content as an image.
Amazon S3 in conjunction with S3Fox, Cyberduck, Jungle Disk and this process allows me to store ALL images I need for my public work in a central location that I own.
My Amazon Web Services account is the center of my cloud storage world. It is important that I store all my vital files here. In the future I know where to find them and won't lost any valuable images I've used in content I have created.