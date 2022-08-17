---
Name: mswsock.dll
Author: Wietze Beukema
Created: '2022-05-21'
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\curl.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\devicecensus.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\ftp.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\hostname.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\nslookup.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\rpcping.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%SYSTEM32%\stordiag.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Google\Chrome\Application\chrome.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft\Edge\Application\msedge.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Mozilla Firefox\firefox.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft Office\root\Office%VERSION%\excel.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft Office\root\Office%VERSION%\outlook.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft Office\root\Office%VERSION%\powerpnt.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft Office\root\Office%VERSION%\winword.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%APPDATA%\Zoom\bin\zoom.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\WindowsApps\MicrosoftTeams%VERSION%\msteams.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
- Path: '%PROGRAMFILES%\Microsoft\EdgeWebView\Application\%VERSION%\msedgewebview2.exe'
  Type: Environment Variable
  Variable: SYSTEMROOT
Resources:
- https://wietze.github.io/blog/save-the-environment-variables
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---
