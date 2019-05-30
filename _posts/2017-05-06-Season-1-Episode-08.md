---
layout: post
permalink: /series1/episode8
series: 1
episode: 8
title: The Binary Times - Series 1 Episode 8
ogg: http://archive.org/download/thebinarytimes_S01E08_Nilim/thebinarytimes_S01E08_Nilim.ogg
mp3: http://archive.org/download/thebinarytimes_S01E08_Nilim/thebinarytimes_S01E08_Nilim.mp3 
image: ThePodcasters8a.jpg
image_alt: The Podcasters in full glory
---
00:24 Intro, changing weather! Wayne and Mark talk about false starts.

01:26 Mark's not been up to a whole lot apart from a course, he's still trying out Linux Mint but is still not sure if he wants to switch, while also mulling over switching out Unity for KDE. He's also set up another VM and put squid on it, as well as wishing he kept better notes.

04:01 Wayne has been fixing full boot partitions on VMs. Extending boot partitions isn't the way to go, here's how he fixed it:

* `uname -r` (to find the currently installed kernel)
* `dpkg --list 'linux-image*' | grep ^ii` (list all installed kernels)
* `sudo apt-get remove linux-image-[insert kernel version you want to remove]` (remove unused kernel version)
* `sudo apt-get autoremove`
* `sudo update-grub`

Taken from [What is the safest way to clean up the boot partition](https://askubuntu.com/questions/345588/what-is-the-safest-way-to-clean-up-boot-partition)

09:24 Wayne goes on to tell us about an article he read on [omgubuntu](http://www.omgubuntu.co.uk/) relating how [Firefox multiprocess is disabled on Ubuntu by default](http://www.omgubuntu.co.uk/2017/05/ubuntu-firefox-multiprocess-enable). This is because the Ubuntu modifications add-on that comes pre-bundled with the browser is not yet compatible with it. Enabling This Makes Firefox More Responsive On Ubuntu

13:03 Are we ready for more of what has Wayne been doing? Wayne rattles through some apt commands and tells us about the advantages of using apt over apt-get. Here are the commands:
* `sudo apt install` (adds progress bar)
* `apt depends firefox` (list all dependencies for firefox)
* `sudo apt remove`
* `sudo apt purge` (removes config files as well as program files)
* `sudo apt autoremove` (remove old unused kernels - SSD space saving)
* `apt show firefox` (show information about the application)
* `apt search mc` (search for all instances of mc)
* `apt --help` (view all apt commands)

17:02 Mark talks about the [Zero Phone](https://hackaday.io/project/19035-zerophone-a-raspberry-pi-smartphone), a $50 smartphone made using the pi zero and arduino, and how it will be available soon on [ crowdsupply.](https://www.crowdsupply.com/arsenijs/zerophone)

21:54 Wayne tells us about his journey with ZFS. ZFS learning links can be found as follows:
* [Ubuntu Wiki on ZFS](https://wiki.ubuntu.com/Kernel/Reference/ZFS)
* [Open-ZFS Bootcamp](https://www.youtube.com/watch?v=mLbtJQmfumI)
* [ZFS 101](https://www.youtube.com/watch?v=OIuWAxkceBY)
* [Becoming a ZFS Ninja Part 1](https://www.youtube.com/watch?v=tPsV_8k-aVU)
* [a friendly guide for building ZFS based SAN/NAS solutions](http://www.zfsbuild.com/2010/05/26/zfs-raid-levels/)

36:26 The conversation moves from filesystems onto backups. Wayne's got a good onsite backup regime in place, Mark blames his "office tidy up" for the lack of his.

40:17 Wayne's concerned he didn't do ZFS the justice it deserves and recommends we watch the youtube video links, while Mark reckons he'll definitely check them out. We'll find out next week... Meanwhile, thank you Sun for ZFS!

43:38 Under the Hood - Mark kicks off under the hood with [screenfetch](https://github.com/KittyKatt/screenFetch), a Bash screenshot information tool. The coolest thing about screenfetch is the ascii art logo (and all the other useful information it provides).

45:34 In terms of "serious command line stuff", check this out (for a silly example): `(cd /tmp &&  ls &gt; list.txt && mv list.txt ~)`

48:05 Wayne tells us about various forms of diff and vimdiff:
* diff is useful for finding the difference between config and text files (i.e between config.txt and config.orig) e.g.:
* `diff config.txt config.orig`
* diff -u adds modification dates and times, unified output, e.g.:
* `diff -u config config.orig`
* vimdiff shows both files opened in vim side by side with differences highlighted - VERY COOL!
* `vimdiff config config.orig`
* e.g. `seq 1 7 f1.txt && seq 1 9 f2.txt && vimdiff f1.txt f2.txt`

49:40 Mark is so happy that these podcasts are made!

50:27 Mark wants to briefly mention the [Humble Very Positive Bundle](https://www.humblebundle.com/very-positive-bundle) before the Irish saying.

51:49 Have we used Conas at&aacute; t&uacute; yet? N&iacute;lim r&oacute; olc in aon chor - Im not too bad at all
