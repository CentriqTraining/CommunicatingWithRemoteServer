# CommunicatingWithRemoteServer
HTML/Javascript dealing with webservices communicating with a remote server.

This project contains just 4 html files:

All files connect to the same web service and use the exact same functions.

- HmlHttpRequest.html - uses pure javascript (no jquery), manually calling up the `XmlHttpRequest` object.  All others do this, but behind the scenes.
- JQuery.html - Uses JQuery 3.5.1 to accomplish the same thing.
- AsyncFetch.html - Uses the new version of ECMAScript, utilizing the `fetch`/`async await`. 
- AsyncFetchMustache.html - Uses the new version of ECMAScript, utilizing the `fetch`/`async await`, and also a cool library called Mustache.js to parse the resulting json by using a template.  Has some really cool features.
