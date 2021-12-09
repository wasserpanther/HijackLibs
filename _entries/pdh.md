---
Name: pdh.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\plasrv.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\relog.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\taskmgr.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\typeperf.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---
