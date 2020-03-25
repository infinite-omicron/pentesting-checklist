---
---

|Configuration and Deployment Management Testing|Test Name|Description|Tools|Status|Comment|
|-----------------------------------------------|---------|-----------|-----|------|-------|
|OTG-CONFIG-001|Network/Infrastructure Configuration|Understand the infrastructure elements interactions, config management for software, backend DB server, WebDAV, FTP in order to identify known vulnerabilities.|{{scanner}}|Not Started||
|OTG-CONFIG-002|Application Platform Configuration|Identify default installation file/directory, Handle Server errors (40*,50*), Minimal Privilege, Software logging.|{{browser}}|Not Started||
|OTG-CONFIG-003|File Extensions Handling for Sensitive Information|Find important file, information (.asa , .inc , .sql ,zip, tar, pdf, txt, etc)|{{browser}}|Not Started||
|OTG-CONFIG-004|Backup and Unreferenced Files for Sensitive Information|Check JS source code, comments, cache file, backup file (.old, .bak, .inc, .src) and guessing of filename|{{scanner}}|Not Started||
|OTG-CONFIG-005|Enumerate Infrastructure and Application Admin Interfaces|Directory and file enumeration, comments and links in source (/admin, /administrator, /backoffice, /backend, etc), alternative server port (Tomcat/8080)|{{proxy}}|Not Started||
|OTG-CONFIG-006|HTTP Methods|Identify HTTP allowed methods on Web server with OPTIONS. Arbitrary HTTP Methods, HEAD access control bypass and XST|{{proxy}}|Not Started||
|OTG-CONFIG-007|HTTP Strict-Transport-Security|Identify HSTS header on Web server through HTTP response header. `curl -s -D- https://domain.com \| grep Strict`|{{proxy}}|Not Started||
|OTG-CONFIG-008|RIA Cross-Domain Policy|Analyse the permissions allowed from the policy files (crossdomain.xml/clientaccesspolicy.xml) and allow-access-from|{{proxy}}|Not Started||
