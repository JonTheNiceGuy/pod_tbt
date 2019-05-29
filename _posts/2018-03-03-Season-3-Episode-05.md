---
title: The Binary Times - Series 3 Episode 5
ogg: http://archive.org/download/thebinarytimes_S03E05_Sneachta/thebinarytimes_S03E05_Sneachta.ogg
mp3: http://archive.org/download/thebinarytimes_S03E05_Sneachta/thebinarytimes_S03E05_Sneachta.mp3 
layout: post
permalink: /series3/episode5
image: ThePodcastersS03E05.png
image_alt: Snow snow snow.
series: 03
episode: 05
---
00:24 Wayne introduces Series 3 Episode 5 of the ice cold binary times. Don't worry listeners if you're having trouble understanding Mark due to his poor audio, he's also speaking Irish!

01:42 Mark tells us about his trials and tribulations with recent nvidia updates on his [Kubuntu 18.04](http://cdimage.ubuntu.com/kubuntu/daily-live/current/) set up. Mark also mentions that Ubuntu 18.04 went into [feature freeze](https://wiki.ubuntu.com/FeatureFreeze) on 1st March, and the first [betas should be released on the 8th March](https://wiki.ubuntu.com/BionicBeaver/ReleaseSchedule).

07:12 Mark's dying to hear what Wayne has been at since he's been keeping it top secret. Wayne's back on the [Raspberry Pi train](https://www.hackster.io/teejK/raspberry-pi-train-times-263e87)! Wayne tells us about ways to manage the manage the memory split between CPU and GPU, and he does this by running the raspi-config utility (you do this by entering `sudo raspi-config` at the command line), choosing option "7. Advanced Options", then choosing "A3 Memory Split" and then slide the amount of memory in MBs you wish to allocate to the GPU, in Wayne's case he uses 16. More information on the raspi-config utility can be found [here](https://www.raspberrypi.org/documentation/configuration/raspi-config.md).

You can also update the firmware on your Raspberry Pi to keep your Raspberry Pi up to date. You can also choose not to, Wayne's gut is telling him that he should. You do this by typing the following: `sudo apt update && sudo apt upgrade -y` and `sudo apt install -y rpi-update` and `sudo rpi-update`.

11:47 Wayne tells us he vehemently dislikes ads and tells us about [Pi-Hole](https://pi-hole.net/), a "black hole for internet advertisements". He goes on to tell us about [PiVPN](http://www.pivpn.io/), a project to provide a simple [openvpn](https://openvpn.net/) setup for the Raspberry Pi. Mark goes on to mention the host file available from [Dan Pollack's website](http://someonewhocares.org/) and the guys expand on their attitudes around advertising. Wayne also mentions [dnscrypt](https://github.com/pi-hole/pi-hole/wiki/DNSCrypt-2.0), which he wasn't able to get working.

23:37 Mark mentions the [Dublin Linux User Group's](http://dlug.ie/) new [telegram group](https://dublinlinux.org/telegram) and their existing social media presence in [Meetup](https://www.meetup.com/Dublin-Linux-User-Group/) and [Facebook](https://www.facebook.com/DublinLinux/) (as well as [discord](https://discord.gg/w7V6A8) and refers back to their interview with [Squid](http://steamcommunity.com/id/OSCowner) and how he is using [proprietary platforms](http://steamcommunity.com/groups/opencommunity) to promote open source software and culture. The guys then talk about their take on social media.

27:16 Wayne brings it back to Linux with some chat on [Ubuntu MATE](https://ubuntu-mate.org/) and the renaming ability in [Caja](https://github.com/mate-desktop/caja) leaves Wayne desiring simple file renaming as found in Windows. Mark decides to ramble on about the differences between [MATE](https://mate-desktop.org/) and [Cinnamon](https://github.com/linuxmint/Cinnamon/) and wonders whether the two projects would be better off merging development resources though he's not so sure how practical that would be. This leads to a discussion on MATE panels and changing them via the [MATE tweak tool](https://github.com/ubuntu-mate/mate-tweak).

35:08 Mark moves the conversation on with a question put to Wayne, asking him about his opinions on KDE Neon. Wayne has only installed it on a VM, he quite likes it, but thinks there are too many options and is not sure if he would change it to be his daily desktop. Time will tell as Wayne is a slow burn.

38:37 Mark contemplates installing [Chakra Linux OS](https://www.chakralinux.org/) on his laptop rather than [Kubuntu 18.04](https://www.youtube.com/watch?v=X7sirKpUjLk), and tells us of some of the [recent changes](https://community.chakralinux.org/t/important-upgrade-of-core-package-groups-and-plasma-5-12-series-by-kde-now-available-in-chakra/7289) Chakra have made in their distribution.

41:26 Wayne introduces Under the Hood, and Mark kicks it off with two, the first being: `ubuntu-drivers -devices`, a command to see what devices on your machine may benefit from proprietary drivers.

Mark feels like [Linus Torvalds in his attitude to NVidia](https://www.wired.com/2012/06/torvalds-nvidia-linux/) and wishes they could be more open in their attitude to open source software. He's hoping to go with [AMD](https://www.amd.com/en) more in the coming years as they are turning towards [open source tools](https://gpuopen.com/).

Mark's second Under the Hood tip is `ubuntu-bug [package]` and he mentions an [Ubuntu Community website](https://help.ubuntu.com/community/ReportingBugs) as a good place to start to report bugs.

45:20 Wayne's under the hood is a command line tool to read metadata from image files. Install using `sudo apt install libimage-exiftool-perl` and in use type `exiftool [name_of_image]`

46:22 Irish saying of the podcast - Mark goes off on a mad one with loadsa Gaeilge! Any way you want to describe the weather:
* T&aacute; s&eacute; fuar - it  is cold
* T&aacute; s&eacute; an-fhuar - it is very cold
* T&aacute; s&eacute; te - it is hot or warm (we don't really do hot in Ireland!)
* T&aacute; s&eacute; fliuch - it is wet
* T&aacute; s&eacute; tirim - it is dry
* T&aacute; s&eacute; dorcha - it is dark
* T&aacute; s&eacute; geal - it is bright

We hoped you enjoyed the podcast!