# Zerava Technologies Inc. — downloads

Binaries and checksums for Zerava software. Source code lives in each
product's own repository. Product pages and documentation: https://www.zeravatech.ca

| Product | Windows | Ubuntu | Docs |
|---|---|---|---|
| Pivot Benchmark | see Releases | see Releases | https://www.zeravatech.ca/docs/pivot-benchmark/ |
| PSE Analyzer | see Releases | see Releases | https://www.zeravatech.ca/docs/pse-analyzer/ |

## Before you run anything

**These builds are not code-signed.** On Windows, SmartScreen shows
"Windows protected your PC"; choose *More info*, then *Run anyway*.
Verify the file first:

```
# Windows (PowerShell)
Get-FileHash .\<file> -Algorithm SHA256

# Ubuntu
sha256sum <file>
```

Compare the result with `SHA256SUMS.txt` attached to the same release.

## Licence

Free to download and use; no redistribution; no warranty. Full text in
[LICENSE.md](LICENSE.md).
