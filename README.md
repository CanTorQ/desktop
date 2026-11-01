# CanTorQ desktop

Installers and updates for the CanTorQ desktop app for Windows.

**Download:** https://cantorq.ca/download/CanTorQ-Setup.exe

This repository holds only the release files. There is no source code here.

- Every release is signed with CanTorQ's own update key. The app checks that
  signature before it installs an update, and refuses one that does not carry
  a valid signature.
- The installer is not yet signed with a Windows code-signing certificate, so
  Windows may show "Windows protected your PC" the first time it is opened.
  Choose "More info", then "Run anyway".
