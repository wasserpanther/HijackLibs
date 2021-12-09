---
Name: dnsapi.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\checknetisolation.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\edpcleanup.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\lpremove.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\msdtc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\netsh.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\nslookup.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\securityhealthservice.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\setupugc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\spoolsv.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\sppextcomobj.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\systempropertiesadvanced.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\systemsettingsadminflows.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\tieringengineservice.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wbengine.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\wkspbroker.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---
