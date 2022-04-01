# Deep-Steganography
The spring-beans package is vulnerable to Remote Code Execution (RCE). The constructor method in the CachedIntrospectionResults class allows the loading of arbitrary classes. A remote attacker can exploit this vulnerability to upload a malicious class and ultimately result in RCE.

More details can be found in Nexus Lifecycle: https://p-nexus-iq.development.nl.eu.abnamro.com:8443/assets/index.html#/vulnerabilities/sonatype-2022-1764

Note: This issue is due to an insufficient fix for CVE-2010-1622.
