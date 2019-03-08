# Quip for Franz
This is the Inofficial Franz recipe for Amazon Quip

Prerequisites (Chrome Policies set for target domains (Kerberos))

Enable
```bash
$ Franz.app/Contents/MacOS/Franz --auth-server-whitelist *.amazon.com,amazon.com --auth-negotiate-delegate-whitelist *.amazon.com,amazon.com,https://amazon.awsapps.com
```
