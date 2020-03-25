---
---

|Cryptography|Test Name|Description|Tools|Status|Comment|
|------------|---------|-----------|-----|------|-------|
|OTG-CRYPST-001|Weak SSL/TSL Ciphers, Insufficient Transport Layer Protection|Identify SSL service, Idectify weak ciphers/protocols (ie. RC4, BEAST, CRIME, POODLE)|{{custom}}|Not Started||
|OTG-CRYPST-002|Padding Oracle|Compare the responses in three different states: Cipher text gets decrypted, resulting data is correct, Cipher text gets decrypted, resulting data is garbled and causes some exception or error handling in the application logic, Cipher text decryption fails due to padding errors.|{{custom}}|Not Started||
|OTG-CRYPST-003|Sensitive Information Sent via Unencrypted Channels|Check sensitive data during the transmission: Information used in authentication (e.g. Credentials, PINs, Session identifiers, Tokens, Cookies…), Information protected by laws, regulations or specific organizational policy (e.g. Credit Cards, Customers data)|{{proxy}}|Not Started||
