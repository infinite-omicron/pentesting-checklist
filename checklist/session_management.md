---
---

|Session Management Testing|Test Name|Description|Tools|Status|Comment|
|--------------------------|---------|-----------|-----|------|-------|
|OTG-SESS-001|Session Management Schema Bypass|SessionID analysis prediction, unencrypted cookie transport, brute-force.|{{proxy}}|Not Started||
|OTG-SESS-002|Cookies Attributes|Check HTTPOnly and Secure flag, expiration, inspect for sensitive data.|{{proxy}}|Not Started||
|OTG-SESS-003|Session Fixation|The application doesn't renew the cookie after a successfully user authentication.|{{proxy}}|Not Started||
|OTG-SESS-004|Exposed Session Variables|Encryption & Reuse of session Tokens vulnerabilities, Send sessionID with GET method ?|{{proxy}}|Not Started||
|OTG-SESS-005|Cross-Site Request Forgery|URL analysis, Direct access to functions without any token.|{{proxy}}|Not Started||
|OTG-SESS-006|Logout Functionality|Check reuse session after logout both server-side and SSO.|{{proxy}}|Not Started||
|OTG-SESS-007|Session Timeout|Check session timeout, after the timeout has passed, all session tokens should be destroyed or be unusable.|{{proxy}}|Not Started||
|OTG-SESS-008|Session Puzzling|The application uses the same session variable for more than one purpose. An attacker can potentially access pages in an order unanticipated by the developers so that the session variable is set in one context and then used in another.|{{proxy}}|Not Started||
