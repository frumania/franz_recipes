# Quip for Franz
This is the Inofficial Franz recipe for Amazon Quip

Requires adjusted chrome policies => enable via custom startup
```bash
$ Franz.app/Contents/MacOS/Franz --auth-server-whitelist *.amazon.com,amazon.com --auth-negotiate-delegate-whitelist *.amazon.com,amazon.com,https://amazon.awsapps.com
```
