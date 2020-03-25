---
---

|Data Validation Testing|Test Name|Description|Tools|Status|Comment|
|-----------------------|---------|-----------|-----|------|-------|
|OTG-INPVAL-001|Reflected Cross-Site Scripting|Check for input validation, Replace the vector used to identify XSS, XSS with HTTP Parameter Pollution.|{{proxy}}|Not Started||
|OTG-INPVAL-002|Stored Cross-Site Scripting|Check input forms/Upload forms and analyze HTML codes, Leverage XSS with BeEF|{{proxy}}|Not Started||
|OTG-INPVAL-003|HTTP Verb Tampering|Craft custom HTTP requests to test the other methods to bypass URL authentication and authorization.|{{proxy}}|Not Started||
|OTG-INPVAL-004|HTTP Parameter Pollution|Identify any form or action that allows user-supplied input to bypass Input validation and filters using HPP|{{proxy}}|Not Started||
|OTG-INPVAL-005|SQL Injection|Union, Boolean, Error based, Out-of-band, Time delay.|{{custom}}|Not Started||
||Oracle||{{custom}}|Not Started||
||MySQL||{{custom}}|Not Started||
||Microsoft SQL||{{custom}}|Not Started||
||PostgreSQL||{{custom}}|Not Started||
||Microsoft Access||{{custom}}|Not Started||
||NoSQL Injection||{{custom}}|Not Started||
|OTG-INPVAL-006|LDAP Injection|`/ldapsearch?user=*`, `user=*user=*)(uid=*))(\|(uid=*`, `pass=password`|{{proxy}}|Not Started||
|OTG-INPVAL-007|ORM Injection|Testing ORM injection is identical to SQL injection testing|{{custom}}|Not Started||
|OTG-INPVAL-008|XML Injection|Check with XML Meta Characters `', " , <>, <!--/-->, &, <![CDATA[ / ]]>, XXE, TAG`|{{proxy}}|Not Started||
|OTG-INPVAL-009|SSI Injection|Presence of .shtml extension, Check for these characters: `< ! # = / . " - >` and `[a-zA-Z0-9]`, include String = `<!--#include virtual="/etc/passwd" -->`|{{proxy}}|Not Started||
|OTG-INPVAL-010|XPath Injection|Check for XML error enumeration by supplying a single quote (`'`), Username: `‘ or ‘1’ = ‘1`, Password: `‘ or ‘1’ = ‘1`|{{proxy}}|Not Started||
|OTG-INPVAL-011|IMAP/SMTP Injection|Identifying vulnerable parameters with special characters (i.e.: `\`, `‘`, `“`, `@`, `#`, `!`, `\|`), Understanding the data flow and deployment structure of the client, IMAP/SMTP command injection (Header, Body, Footer)|{{proxy}}|Not Started||
|OTG-INPVAL-012|Code Injection|Enter OS commands in the input field: `?arg=1; system('id')`|{{proxy}}|Not Started||
||Local File Inclusion||{{manual}}|Not Started||
||Remote File Inclusion||{{manual}}|Not Started||
|OTG-INPVAL-013|Command Injection|Understand the application platform, OS, folder structure, relative path and execute OS commands on a Web server, `%3Bcat%20/etc/passwd`, `test.pdf+\|+Dir C:\`|{{proxy}}|Not Started||
|OTG-INPVAL-014|Buffer Overflow|Testing for heap overflow vulnerability, Testing for stack overflow vulnerability, Testing for format string vulnerability|{{scanner}}|Not Started||
||Heap Overflow||{{manual}}|Not Started||
||Stack Overflow||{{manual}}|Not Started||
||Format String||{{manual}}|Not Started||
|OTG-INPVAL-015|Incubated Vulnerabilities|File Upload, Stored XSS , SQL/XPATH Injection, Misconfigured servers (Tomcat, Plesk, Cpanel)|{{proxy}}|Not Started||
|OTG-INPVAL-016|HTTP Splitting/Smuggling|`param=foobar%0d%0aContent-Length:%200%0d%0a%0d%0aHTTP/1.1%20200%20OK%0d%0aContent-Type:%20text/html%0d%0aContent-Length:%2035%0d%0a%0d%0a<html>Sorry,%20System%20Down</html>`|{{proxy}}|Not Started||
