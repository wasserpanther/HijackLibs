---
Name: authz.dll
Author: Wietze Beukema
Created: 2021-02-27
Vendor: Microsoft
ExpectedLocations:
- '%SYSTEM32%'
- '%SYSWOW64%'
VulnerableExecutables:
- Path: '%SYSTEM32%\easinvoker.exe'
  Type: Sideloading
  AutoElevate: true
- Path: '%SYSTEM32%\vssvc.exe'
  Type: Sideloading
- Path: '%SYSTEM32%\whoami.exe'
  Type: Sideloading
Resources:
- https://wietze.github.io/blog/hijacking-dlls-in-windows
Acknowledgements:
- Name: Wietze
  Twitter: '@wietze'
---
