---
layout: wiki
title: Building
order: 3
parent: /wiki/index.html
---
Starting with `3.0.0` release, SharpDX requires only to have the latest Visual Studio with updates installed (for `3.0.0`, the Windows SDK required is `10.0.10586.0`)

The project contains two solutions:
- `SharpDX-Desktop.sln` to compile assemblies for the `.NET 4.5+` desktop platform
- `SharpDX-StoreApp.sln` to compile assemblies for the `PCL .NET 4.6+` platform (including StoreApps, UWP and PCL)

For previous version (e.g 2.6.x), you will need:

- [Microsoft Windows SDK for Windows 7 and .NET Framework 4 (ISO)](http://www.microsoft.com/en-us/download/details.aspx?id=8442)
- [DirectX June SDK 2010](www.microsoft.com/en-us/download/details.aspx?id=6812)
