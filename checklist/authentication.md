---
---

|Authentication Testing|Test Name|Description|Tools|Status|Comment|
|----------------------|---------|-----------|-----|------|-------|
|OTG-AUTHN-001|Credentials Transported over Unencrypted Channel|Check referrer whether its HTTP or HTTPs. Sending data through HTTP and HTTPS.|{{proxy}}|Not Started||
|OTG-AUTHN-002|Default Credentials|Testing for default credentials of common applications, Testing for default password of new accounts.|{{proxy}}|Not Started||
|OTG-AUTHN-003|Weak Lock-out Mechanism|Evaluate the account lockout mechanism’s ability to mitigate brute force password guessing, Evaluate the unlock mechanism’s resistance to unauthorized account unlocking|{{browser}}|Not Started||
|OTG-AUTHN-004|Authentication Schema Bypass|Force browsing (/admin/main.php, /page.asp?authenticated=yes), Parameter Modification, Session ID prediction, SQL Injection|{{proxy}}|Not Started||
|OTG-AUTHN-005|Remember Password Functionality|Look for passwords being stored in a cookie. Examine the cookies stored by the application. Verify that the credentials are not stored in clear text, but are hashed. Autocompleted=off?|{{proxy}}|Not Started||
|OTG-AUTHN-006|Browser Cache Weakness|Check browser history issue by clicking "Back" button after logging out. Check browser cache issue from HTTP response headers (Cache-Control: no-cache)|{{proxy}}|Not Started||
|OTG-AUTHN-007|Weak Password Policy|Determine the resistance of the application against brute force password guessing using available password dictionaries by evaluating the length, complexity, reuse and aging requirements of passwords.|{{proxy}}|Not Started||
|OTG-AUTHN-008|Weak Security Question/Answer|Testing for weak pre-generated questions, Testing for weak self-generated question, Testing for brute-forcible answers (Unlimited attempts?)|{{browser}}|Not Started||
|OTG-AUTHN-009|Weak Password Change/Reset Functionality|Test password reset (Display old password in plain-text?, Send via email?, Random token on confirmation email ?), Test password change (Need old password?), CSRF vulnerability ?|{{browser}}, {{proxy}}|Not Started||
|OTG-AUTHN-010|Weaker Authentication in Alternative Channel|Understand the primary mechanism and Identify other channels (Mobile App, Call center, SSO)|{{browser}}|Not Started||
