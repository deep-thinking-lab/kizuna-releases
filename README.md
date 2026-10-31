# Kizuna releases

Signed release binaries for the Kizuna runner and tools.

Install the runner with the installer from https://kizuna.codes, which verifies every download.

To verify a download by hand, check `SHA256SUMS` against its minisign signature, then check the archive:

```
minisign -V -P RWTZtRmNKVOR0U5V5FxnqiwHfz7nP/olquYcs6jQDckepXx7H7tzwxEt -m SHA256SUMS
sha256sum -c --ignore-missing SHA256SUMS
```

Release signing key ID: D19153298D19B5D9.
