---
layout: post
title: Github Releases New API Version
url: http://kinlane.com/2011/04/28/github-releases-new-api-version/
image: http://kinlane-productions.s3.amazonaws.com/github/github-round.png
---
{% include JB/setup %}

Using the new <a title="Github API" href="http://developer.github.com/v3/">Github API</a> users canmanage labels, issue comments, milestones, and events.
The new API also has full support for <a title="Gists" href="https://gist.github.com/">Gists</a>.
They've also made several updates to their RESTful approach:
<ul>
     <li>URLs are simpler and more consistent: https://api.github.com/repos/github/gollum/issues.json.
     </li>
     <li>Resources return url fields so that clients don't have to build URLs.
     </li>
     <li>Create/Update actions take JSON, instead of POST parameters.
     </li>
     <li>Pagination and Rate Limiting info is returned on every applicable request.
     </li>
     <li>JSON-P requests get a special payload with header information.
     </li>
</ul>The new version of the API only supports JSON as the request and response format.
There is also a new daily cap of 5000 requests for the API.
There are still supporting API v2, and will announce deprecation plans soon.