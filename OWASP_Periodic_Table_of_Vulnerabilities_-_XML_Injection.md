[Return to Periodic Table Working
View](OWASP_Periodic_Table_of_Vulnerabilities#Periodic_Table_of_Vulnerabilities "wikilink")

## XML Injection

### Root Cause Summary

XML documents are generated by including dynamic data without proper
encoding.

### Browser / Standards Solution

None

### Perimeter Solution

None

### Generic Framework Solution

The framework should provide safe libraries for constructing and
manipulating XML documents that automatically encode all dynamic data.
The framework should disallow any direct access to raw XML.

### Custom Framework Solution

None

### Custom Code Solution

None

### Discussion / Controversy

[Cross-Site Scripting / HTML
Injection](OWASP_Periodic_Table_of_Vulnerabilities_-_Cross-Site_Scripting_\(XSS\) "wikilink")
is a special case of XML injection.

### References

[Testing for XML Injection
(OWASP-DV-008)](Testing_for_XML_Injection_\(OWASP-DV-008\) "wikilink")
[XML Injection
(WASC)](http://projects.webappsec.org/w/page/13247004/XML%20Injection)
[XML Injection (CWE)](http://cwe.mitre.org/data/definitions/91.html)