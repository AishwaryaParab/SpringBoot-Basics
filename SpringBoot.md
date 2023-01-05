# Errors Faced

```
sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
```

```
I/O error on GET request for "https://jsonplaceholder.typicode.com/posts": PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target; nested exception is javax.net.ssl.SSLHandshakeException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target] with root cause
```

# Solutions

- https://stackoverflow.com/questions/9619030/resolving-javax-net-ssl-sslhandshakeexception-sun-security-validator-validatore

- https://www.ibm.com/support/pages/sunsecurityvalidatorvalidatorexception-pkix-path-building-failed-sunsecurityprovidercertpathsuncertpathbuilderexception-unable-find-vali