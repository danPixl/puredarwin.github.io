![](/puredarwin.png)

[Darwin](http://en.wikipedia.org/wiki/Darwin_%28operating_system%29) is the Open Source operating system from Apple that forms the basis for macOS, and PureDarwin is a community project to make Darwin more usable (some people think of it as the informal successor to OpenDarwin).

One current goal of this project is to provide a useful bootable IMG and Virtual Machine of Darwin 10.x
Another goal of this project is to provide additional documentation. [More](https://github.com/PureDarwin/PureDarwin/wiki/About)...

 


# Teaser the Darwin Community!

## Here's a screenshot of Our Latest Build!
![](Screenshots/Screenshot-2018-03-02.png)
##### It's all most there guys!!! It's a work in progress but it's going along and all built from open source code based on 10.13.3.

Documentation and quick hints
-----------------------------
Please see our [PureDarwin Wiki](https://github.com/PureDarwin/PureDarwin/wiki/). It would be very kind if you could fix the wiki as we have links that are broken.

See the [Changelog](https://github.com/PureDarwin/PureDarwin/wiki/_history) for recent updates of this Wiki.

*NEW!* Getting the code
-------------------------
We have [GitHub](https://github.com/PureDarwin/), and encourage visitors to use the GitHub repository for both contribution, and checking out the latest build source. 

Additionally, as an interim measure, a [version of PureDarwin Xmas](https://github.com/PureDarwin/LegacyDownloads/releases/download/PDXMASNBE01/NewBootEnvironment-XMas-1.7z) with a fixed boot sector, which is compatible with QEMU is also available.

## **Something to the Open Source Community!**

### **Here's a [Guide](https://github.com/PureDarwin/Building-XNU-16.7-Kernel-Guide/) on Building XNU of the 16.7 (10.12.6) Kernel!** 

Status
------

PureDarwin is currently working on AHCI and eMMC family/drivers for Darwin only - they will not support/work on Apple's macOS. We have a PoC(Proof of Concept) of PureDarwin 2.2 qemu image that's based on Apple's open source code of [macOS 10.10.5](http://opensource.apple.com/release/os-x-10105/) that is only currently available to those who join our IRC channel #puredarwin on freenode. 

Update: Hey, guys, we're still moving along we will be providing an SDK that is native of an Apple release on opensource.apple.com and a modified version that is PureDarwin targeted as we are working on XNU modified Kernel with some other BSD/POSIX features that don't require us to rely on Apple's proprietary code that they'll never release.

We are looking for supporters/coders that can help bring about faster Development of PureDarwin while showing Apple that there is still a community of Open Source Darwin Supporters that would like to see more openness from them whether it be from them releasing Binary Drivers for our use as they once did or open source projects like libxpc/launchd again.

[PureDarwin's Current Build Status](https://puredarwin.github.io/Status.md)

### PureDarwin IRC Channel!
Please join us on freenode.net #puredarwin for our info we have USA/UK/Europe Devs who which can receive hardware.
### New PureDarwin Community Forum!
Please come join Us over at [PureDarwin Developers](https://www.pd-devs.org)

FAQ
-------

What is Darwin?

Darwin is the Open Source operating
system from Apple that forms the
basis for Mac OS X, and PureDarwin is
a community project to make Darwin
more usable (some people think of it
as the informal successor to OpenDarwin).

What is PureDarwin?

The goal of this project is to make
Darwin more usable by providing an
installation ISO, documentation, and
add-on software. You are welcome to
join #puredarwin on irc.freenode.net
if you would like to join PureDarwin
development and to add to
www.puredarwin.org

How usable is PureDarwin?

PureDarwin can run on VMware as well
as real Intel-based hardware. We are
successfully running a web server, have
built hundreds of software packages
with MacPorts running on PureDarwin,
including ssh, apache2, tightvnc, Xfce,
and others.

Why spend time on Darwin?

For learning and fun.

How does PureDarwin relate to the
former OpenDarwin project?

Although some people have been
seeing PureDarwin as the informal
successor to OpenDarwin, there is no
official relationship other than the fact
that OpenDarwin and PureDarwin are
both downstream Darwin projects.
Also, it is no secret that PureDarwin
would not exist if OpenDarwin had not
closed down. Coming later in time,
PureDarwin is in the fortunate position
to be able to benefit from the valuable
contributions that were rooted in the
OpenDarwin project.

How does PureDarwin relate to the
DarwinBuild project?

DarwinBuild is one of PureDarwin‘s
main upstream projects.

What does the "Pure“ in PureDarwin mean?

Pure as in beer! It means that we just use components specifically released by Apple for use with Darwin, as well as other open source components (called "upstream code“). Specifically, it means that we do not use any components from macOS. It also means that we try to stay as close as possible to the "outside world“ as in macOS (e.g., regarding the choice of compilers, options, etc.). It does not mean, however, that we do not modify and add to the upstream code, to the extent that the respective licenses allow.

How can I help PureDarwin?

Pretty much on all fronts. Especially if
you are skilled in C, C++, ObjC, Mac OS
X, BSD, etc. you should consider joining
#puredarwin on irc.freenode.net

Credits
-------

We would like to thank
-   Apple, Inc. for releasing Darwin as Open Source 
-   kvv and _wms for their continuing help
-   David Elliott for his work on boot-132
-   The Chameleon team for their work on boot-132
-   The xnu-dev team for their work on the XNU kernel
-   Stuart Crook for his work on PureFoundation
-   Guillaume Verdeau for his work on X.Org
-   [Rafirafi](https://github.com/rafirafi) for his work on Generic Platform and PDCrypto kexts
-   [InSaneDarwin](https://github.com/csekel/) for his work on AHCI and eMMC Family/Drivers(still in active private development)
-   Mac OS Forge 
-   The DarwinBuild project 
-   The MacPorts project
-   The folks at #macosforge, #macports, #macdev, #opendarwin, #puredarwin, 
-   Everyone else contributing to Darwin 

Contact Us! 
-------
Admins
-  Ferdinand Klinzer - bart@pd-devs.org
-  Clifford Sekel - insanedarwin@pd-devs.org

Core Dev's
-  Ethan Sherriff - libsystem_ethan@pd-devs.org
-  Avi Saven - avisaven@pd-devs.org
-  William Kent - wjk@pd-devs.org

{% include footer.html %}

© 2017 PureDarwin Foundation 
