# WinUSBNet

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/FrankeCoffee/winusbnet/build.yml)
[![NuGet version (FrankeCsTools.WinUSBNet)](https://img.shields.io/nuget/v/FrankeCsTools.WinUSBNet.svg)](https://www.nuget.org/packages/FrankeCsTools.WinUSBNet/)
[![NuGet](https://img.shields.io/nuget/dt/FrankeCsTools.WinUSBNet.svg)](http://nuget.org/packages/FrankeCsTools.WinUSBNet)

![Net48](https://badgen.net/badge/Framework/.Net&nbsp;4.8/blue) ![Net481](https://badgen.net/badge/Framework/.Net&nbsp;4.8.1/blue) ![NetCore10](https://badgen.net/badge/Framework/NetCore&nbsp;10/blue)

WinUSBNet is a .NET class library that provides easy access to the WinUSB API from C#, VB.NET and other .NET languages. WinUSB is a user mode API available for Windows XP, Vista and 7 (XP will require an update), allowing low level access to USB devices such as control transfers and reading from and writing to endpoints.

Please note that there is at least one different project with the same name (at codeplex), this libary is not related.

## Changes of this fork

This is a fork of [WinUSBNet](https://github.com/madwizard-thomas/winusbnet)  
Home of forked Repo: FrankeCsTools.[WinUSBNet](https://github.com/FrankeCoffee/winusbnet)  
Nuget package: [FrankeCsTools.WinUSBNet](https://www.nuget.org/packages/FrankeCsTools.WinUSBNet)

- Assembly signed with strong name
- Added support for .NET Framework 4.8 and .NET Framework 4.8.1
- Added support for .NET 10.0
- Support for older .NET Framework 3.5, 4.5 removed
- Project upgraded to Visual Studio 2026
- No functional changes or improvements.

The content below is the original readme from the original project.

---

## Download

[Download latest release](https://github.com/madwizard-thomas/winusbnet/releases/latest)

## Status

The library is *stable*. If you find any bugs or problems please report them using the issue tracker or add a pull request if you have fixed something yourself.

## Features

- MIT licensed with C# source code available (free for both personal and commercial use)
- CLS compliant library (usable from all .NET languages such as C#, VB.NET and C++.NET)
- Synchronous and asynchronous data transfers
- Support for 32-bit and 64-bit Windows versions
- Notification events for device attachment and removal
- Support for multiple interfaces and endpoints
- Intellisense documentation

## Related documentation

- [Library reference online](http://madwizard-thomas.github.io/winusbnet/docs/)
- [Online wiki with short howto](https://github.com/madwizard-thomas/winusbnet/wiki)
- [Changelog](Changelog.md)
- [WinUSB overview](https://docs.microsoft.com/en-us/windows-hardware/drivers/usbcon/winusb)
- [How to Access a USB Device by Using WinUSB Functions](https://docs.microsoft.com/en-us/windows-hardware/drivers/usbcon/using-winusb-api-to-communicate-with-a-usb-device)
- [Jan Axelson's page on WinUSB](http://janaxelson.com/winusb.htm)
