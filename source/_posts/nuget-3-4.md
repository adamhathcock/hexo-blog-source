---
title: nuget-3-4
date: 2016-03-31 09:46:11
tags:
  - nuget
  - sharpcompress
---
## Project.json and SharpCompress

I've long loved project.json but it's only really now coming together.  There seems to finally be a [spec up for it.](https://docs.nuget.org/Consume/ProjectJson-Intro) The [major sections](https://docs.nuget.org/Consume/ProjectJson-Format) explained too.

With [NuGet 3.4](http://blog.nuget.org/20160330/Introducing-NuGet-3.4.html) I think I'll make SharpCompress use project.json only as it's much simplier than multiple csproj projects.  Let's see if it works.