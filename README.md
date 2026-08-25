# NextDraw Releases

Public mirror of Bantam Tools NextDraw software downloads.

## Canonical source

The authoritative download location for NextDraw software is
[bantam.tools/ndsoft](https://bantam.tools/ndsoft), served from
`software-download.bantamtools.com`. This repository is a **mirror**.

If the two ever disagree, the canonical source is correct.

## Current downloads

Each item below is a separate, independently downloadable file. These links always
resolve to the most recent release, and are stable and safe to bookmark, script
against, or document.

| Item | Permalink |
|---|---|
| NextDraw Python API & CLI | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_api.zip |
| NextDraw for macOS (installer) | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_mac_install.zip |
| NextDraw for macOS | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_mac.zip |
| NextDraw for Windows (installer) | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_win_install.zip |
| NextDraw for Windows | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_win.zip |
| NextDraw for Linux (x86_64) | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_linux_x86.zip |
| NextDraw for Linux (ARM) | https://github.com/bantamtools/nextdraw-release/releases/latest/download/nextdraw_linux_arm.zip |

<!-- Every item listed here MUST be attached to every release, or its permalink will
     404 as soon as a release omits it. Asset filenames are permanent and must never
     carry a version number; the version lives inside the archive. -->

## Specific versions

To pin to an exact version, use the tag in place of `latest`:

    https://github.com/bantamtools/nextdraw-release/releases/download/<tag>/<filename>

Every release carries the complete set of files listed above as of that date, so a
single release is a self-contained snapshot of the full distribution.

Browse all releases: https://github.com/bantamtools/nextdraw-release/releases

## Verifying a download

Each release publishes SHA-256 checksums for its assets in `SHA256SUMS.txt`:

    shasum -a 256 -c SHA256SUMS.txt              # macOS / Linux
    certutil -hashfile nextdraw_api.zip SHA256   # Windows, one file at a time

## Documentation and support

Documentation is included inside each download. For product information and support,
see bantamtools.com.

## Terms

NextDraw software is distributed under its accompanying license terms; see the
documents included in each download. Publication here does not alter those terms.
