---
title: SharpCompress 0.11.6
date: 2016-04-07 09:51:38
tags:
  - sharpcompress
---
# SharpCompress 0.11.6

Another minor release.

* Bug fix for global header in Tar
* Writers now have a leaveOpen `bool` overload.  They won't close streams if not-requested to.

[NuGet](https://www.nuget.org/packages/sharpcompress/0.11.6)

I really need to implement [AppVeyor](https://www.appveyor.com/) or [Travis CI](https://travis-ci.org/) and project.json.  One step at a time I guess.