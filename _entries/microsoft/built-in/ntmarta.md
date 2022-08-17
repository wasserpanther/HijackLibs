---
Name: ntmarta.dll
Author: Wietze Beukema
Created: 2022-08-14
Vendor: Microsoft
ExpectedLocations:
  - "%SYSTEM32%"
  - "%SYSWOW64%"
VulnerableExecutables:
- Path: '%PROGRAMFILES%\Google\Chrome\Application\chrome.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft\Edge\Application\msedge.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft\EdgeWebView\Application\%VERSION%\msedgewebview2.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
Resources:
- https://wietze.github.io/blog/save-the-environment-variables
Acknowledgements:
  - Name: Wietze
    Twitter: "@wietze"
---
