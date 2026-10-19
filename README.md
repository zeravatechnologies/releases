# Zerava Technologies Inc. — downloads

Built files and checksums for Zerava software. This repository holds no source
code: each product is built by GitHub Actions from a tagged commit in its own
public repository, and the files are attached here as release assets.
Product pages and documentation: https://www.zeravatech.ca

| Product | Current version | Licence | Source | Docs |
|---|---|---|---|---|
| PSE Analyzer | [0.3.2](https://github.com/zeravatechnologies/releases/releases/tag/pse-analyzer-v0.3.2) | GPL-3.0-or-later | [pse-analyzer](https://github.com/zeravatechnologies/pse-analyzer) | https://www.zeravatech.ca/docs/pse-analyzer/getting-started/ |
| Pivot Benchmark | [0.9.1-preview](https://github.com/zeravatechnologies/releases/releases/tag/pivot-benchmark-v0.9.1-preview) | GPL-3.0-or-later | [pivot-bench](https://github.com/zeravatechnologies/pivot-bench) | https://www.zeravatech.ca/docs/pivot-benchmark/getting-started/ |

Each release offers a Windows build and an Ubuntu `.deb`, with a
`SHA256SUMS.txt` beside them.

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

The current releases are free and open source under the GNU General Public
License, version 3 or later ([LICENSE.md](LICENSE.md)). Every download carries
its own `LICENSE.md` and a `NOTICE` with an authorship term under section 7(b)
of the GPL that must be kept in every copy.

Two earlier releases, PSE Analyzer 0.3.1 and Pivot Benchmark 0.9.0-preview,
were published under the earlier Zerava Technologies Inc. Software Licence 1.0
([LICENSE-ZERAVA-1.0.md](LICENSE-ZERAVA-1.0.md)), which applies to them only.
Details in [NOTICE](NOTICE).
