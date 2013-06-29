---
layout: post
title: Amazon Web Services Offers Server Side Encryption for Amazon S3
url: http://kinlane.com/2011/10/05/amazon-web-services-offers-server-side-encryption-for-amazon-s3/
image: http://kinlane-productions.s3.amazonaws.com/amazon/amazon-s3-encryption.png
---
{% include JB/setup %}

Amazon S3 Server Side Encryption employs multi-factor encryption, with each object encrypted with a unique key, and as an additional safeguard, this key is itself encrypted with a regularly rotated master key. Amazon S3 Server Side Encryption uses one of the strongest block ciphers available -- 256-bit Advanced Encryption Standard (AES-256).
You can start using Amazon S3 Server Side Encryption in the AWS Management Console:
<ol class="mainlist">
     <li>Under the Amazon S3 tab, use the upload dialog to add files to be uploaded.
     </li>
     <li>In the Set Details section of the upload dialog, set the Use Server Side Encryption checkbox property.
     </li>
     <li>Start Upload. The files will be encrypted and stored in Amazon S3.
     </li>
</ol>If you prefer to manage your own encryption keys, you can also make use of the client libraries for encryption provided by Amazon. To learn more, visit the <a title="Amazon S3 Encryption Client Page" href="http://www.amazon.com/gp/r.html?R=2SXVU4T3VRUWB&amp;C=1AJGXG7AWCE0N&amp;H=B9OTOYJPABEMCLJGAHXFZEK3ATEA&amp;T=C&amp;U=http%3A%2F%2Fdocs.amazonwebservices.com%2FAWSJavaSDK%2Flatest%2Fjavadoc%2Fcom%2Famazonaws%2Fservices%2Fs3%2FAmazonS3EncryptionClient.html" target="_blank">Amazon S3 Encryption client page</a>.