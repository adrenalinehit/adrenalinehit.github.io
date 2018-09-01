---
layout: post
title:  "SignalR dotnet core"
date:   2018-09-01 21:00:00 +0100
categories: dotnet hacking
---
Some suff will follow on dotnet core and ASP.NET core SignalR changes.

dotnet core 2.1

.NET Core SDK (reflecting any global.json):
 Version:   2.1.401
 Commit:    91b1c13032

Runtime Environment:
 OS Name:     ubuntu
 OS Version:  18.04
 OS Platform: Linux
 RID:         ubuntu.18.04-x64
 Base Path:   /usr/share/dotnet/sdk/2.1.401/

Host (useful for support):
  Version: 2.1.3
  Commit:  124038c13e

.NET Core SDKs installed:
  1.0.4 [/usr/share/dotnet/sdk]
  2.1.401 [/usr/share/dotnet/sdk]

.NET Core runtimes installed:
  Microsoft.AspNetCore.All 2.1.3 [/usr/share/dotnet/shared/Microsoft.AspNetCore.All]
  Microsoft.AspNetCore.App 2.1.3 [/usr/share/dotnet/shared/Microsoft.AspNetCore.App]
  Microsoft.NETCore.App 1.0.5 [/usr/share/dotnet/shared/Microsoft.NETCore.App]
  Microsoft.NETCore.App 1.1.2 [/usr/share/dotnet/shared/Microsoft.NETCore.App]
  Microsoft.NETCore.App 2.1.3 [/usr/share/dotnet/shared/Microsoft.NETCore.App]

To install additional .NET Core runtimes or SDKs:
  https://aka.ms/dotnet-download

Check out the [tutorial here][tutorial]
Auto [reconnects here][reconnects]

[tutorial]: https://docs.microsoft.com/en-us/aspnet/core/tutorials/signalr?view=aspnetcore-2.1&tabs=visual-studio
[reconnects]: https://www.radenkozec.com/net-core-signalr-automatic-reconnects/