---
description: >-
  The recent addition of scripted REST APIs and API version support has really
  made working with ServiceNow integrations as easy and robust as they should be
  in this day of highly connected systems. Managing, supporting, and deprecating
  API versions can be a challenge if you don't have access to usage statistics.
  The Helsinki release takes API management to a new level.
dateModified: '2016-08-10T18:11:53.041Z'
datePublished: '2016-08-10T18:12:10.229Z'
title: HelsinkiHint - API Stats
author: []
publisher: {}
via: {}
starred: false
sourcePath: _posts/2016-08-10-helsinkihint-api-stats.md
inFeed: true
hasPage: false
inNav: false
_type: MediaObject

---
# HelsinkiHint - API Stats

The recent addition of [scripted REST APIs][0] and [API version support][1] has really made working with ServiceNow integrations as easy and robust as they should be in this day of highly connected systems. Managing, supporting, and deprecating API versions can be a challenge if you don't have access to usage statistics. The [Helsinki release][2] takes API management to a new level.

You can now access detailed usage trends for all client requests to an instance's REST and SOAP endpoints. Trending by API type, endpoint, method, and version are all available via the new [Web API Usage Overview][3] dashboard.

Let's take a look at the usage dashboard for the "cavu/test" REST API. As with all ServiceNow homepages and dashboards, these are fully customizable.

Probably one of the most useful reports for an API owner is a summary of requests by API version. Depending on the application lifecycle and support model of your API, it can be extremely valuable to understand whether clients are requesting specific versions or using the default published version.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/ed6638b3-6492-454d-9492-2a7b72881783.png)

Another useful trend that helps define your maintenance and support needs is the trend of total requests for a given API.
![](https://imgflo.herokuapp.com/graph/vahj1ThiexotieMo/d981be51983b3c5fe54a14ded19947ae/croprotate.png?cropheight=731&cropwidth=1404&degrees=0&input=https%3A%2F%2Fthe-grid-user-content.s3-us-west-2.amazonaws.com%2F06713106-3252-41e5-a547-b2fa2c758972.png&x=0&y=2)

The last piece of commonly used data will help you understand the usage by API method.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/f26da969-50e3-4fe0-8dbc-e35327670b06.png)

I can't spill the beans, but you should be on the lookout for even more REST related analytics and tools coming in Istanbul.

[0]: https://docs.servicenow.com/bundle/geneva-servicenow-platform/page/integrate/custom_web_services/concept/c_CustomWebServices.html
[1]: https://docs.servicenow.com/bundle/geneva-servicenow-platform/page/integrate/inbound_rest/concept/c_RESTAPIVersion.html
[2]: https://docs.servicenow.com/bundle/helsinki-release-notes/page/release-notes/helsinki-release-notes.html
[3]: https://docs.servicenow.com/bundle/helsinki-servicenow-platform/page/integrate/inbound-web-services/concept/c_APIAnalytics.html