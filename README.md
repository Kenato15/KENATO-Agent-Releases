# KENATO Agent Releases

Official binary-only distribution repository for KENATO Agent customer installers and controlled MVP pilots.

## MVP pilot channel

Current pilot packages are pre-release builds intended for controlled external testing. They are **not** final public installers and may be **unsigned**, which can trigger Windows SmartScreen / Unknown Publisher warnings.

Before running a pilot package:

1. Download the ZIP together with its `.sha256.txt` and manifest.
2. Verify the ZIP SHA-256 matches both the checksum file and the manifest.
3. Extract the ZIP.
4. Run **Start KENATO Agent.cmd**.
5. Complete KENATO account pairing in the browser.

The local Agent does not grant standalone access to KENATO capabilities. Cloud authorization, tenant binding, plan/quota enforcement, consent, and Execution Grants remain authoritative.

Source code is intentionally not published in this repository.
