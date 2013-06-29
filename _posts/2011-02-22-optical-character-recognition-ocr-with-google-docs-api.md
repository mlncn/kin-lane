---
layout: post
title: Optical Character Recognition OCR with Google Docs API
url: http://kinlane.com/2011/02/22/optical-character-recognition-ocr-with-google-docs-api/
image: http://kinlane-productions.s3.amazonaws.com/mimeo/PDF-OCR.png
---
{% include JB/setup %}

<ul>
     <li>PDF Document (application/pdf)
     </li>
     <li>JPG Image (image/jpeg)
     </li>
     <li>PNG Image (image/png)
     </li>
     <li>GIF Image (image/gif)
     </li>
</ul>OCR is an experimental API feature and has a quota in place, limiting the number of calls that can be made. API quota is higher for Google Apps for Business users.
OCR is available through the API by including the ocr=true parameter when uploading a file, then produces a separate Google Docs with extracted text for each uploaded PDF or Image.