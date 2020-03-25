---
---

|Authorization Testing |Test Name|Description|Tools|Status|Comment|
|----------------------|---------|-----------|-----|------|-------|
|OTG-AUTHZ-001|Directory Traversal/File Include|dot-dot-slash attack (`../`), Directory traversal, Local File inclusion/Remote File Inclusion.|{{proxy}}|Not Started||
|OTG-AUTHZ-002|Authorization Schema Bypass|Access a resource without authentication?, Bypass ACL, Force browsing (/admin/adduser.jsp)|{{proxy}}|Not Started||
|OTG-AUTHZ-003|Privilege Escalation|Testing for role/privilege manipulate the values of hidden variables. Change some param groupid=2 to groupid=1|{{proxy}}|Not Started||
|OTG-AUTHZ-004|Insecure Direct-Object Reference|Force changing parameter value (?invoice=123 -> ?invoice=456)|{{proxy}}|Not Started||
