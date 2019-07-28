# Cloudonix WebRTC Client Widget Demo #
This repository contains a "JavaScript Pure" web widgit implementation of the Cloudonix WebSDK. This demo will create a 
 floating button, located at the bottom left side of your broswer screen. Once clicked, a 'dialer' type screen will appear
 allowing you to click a 'green call button'. Once clicked, the widgit will activate a SIP over WebSocket session to the 
 Cloudonix WebRTC endpoint for further processing.

## Prerequisites
This source requires the following:

- A functional Cloudonix Tenant account
- A functional Cloudonix namespace (domain) associated to the above Tenant account
- A functional Cloudonix subscriber associated to the above domain
- A functional Internet connection
- A WebRTC compatible browser (Chrome, Firefox or a Chromium based browser)

## Setting up
In order to get this demo to work correctly, you will be required to modify the `cloudonixWidgit.html` file and defined 
information as described below:

Around line 10:
```html
<script>
    var myDestination = 'the.destination.number.you.would.like.to.dial';
    var myCloudonixDomain = 'your.cloudonix.namespace';
    var myCloudonixSubscriber = 'the.assigned.subscriber.id';
    var myCloudonixPassword = 'the.assigned.subscriber.password';
</script>
```

That's it - you're ready to go. 

## Issues, Contributions and more
We welcome you to provide us with feedback and potentially issues and even pull-requests. This code is released to the 
community, to ensure full visibility to the community of our tools and how they work.

## General ##
### License ###
Copyright 2019 Cloudonix, Inc. (Released under the MIT license)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated 
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the 
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit 
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the 
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE 
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS 
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR 
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Disclaimer ###
The following source code is provided as-is and is provided as a learning tool, as to how to use the Cloudonix WebRTC 
endpoints for building a WebRTC Web Widgit. Cloudonix makes no claim to the stability or reliability of this source code,
it is provided as a 'conceptual implementation'. Shoud you decide to use this source code in production deployments, 
it your responsibility to verify its quality and applicability to your usage.

 