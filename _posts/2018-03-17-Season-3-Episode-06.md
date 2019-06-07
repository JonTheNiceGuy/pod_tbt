---
title: The Binary Times - Series 3 Episode 6
ogg: http://archive.org/download/thebinarytimes_S03E06_Padraig/thebinarytimes_S03E06_Padraig.ogg
mp3: http://archive.org/download/thebinarytimes_S03E06_Padraig/thebinarytimes_S03E06_Padraig.mp3 
layout: post
permalink: /series3/episode6
image: ThePodcastersS03E06a.png
image_alt: Mark hasnt prepared anything this week!!
series: 03
episode: 06
post_time: "11:30:00"
---
00:24 A very festive Irish greeting introduces the show this week, with suitable translations for our non-Gael-goer listeners by Wayne. It's cold in Bristol and it's cold in Kilkishen, the beast from the east is flexing its muscles once more it seems and snow is on the way.

02:00 Mark tells us he's been busy at work! What a suprise! He also tells us that a new radio they have at work is basically a linux box with a software defined radio, but that's all the details he has. And there's nothing in the shownotes explaining it further! :-)

03:56 At least Wayne's been busy in the open source world so he'll be able to carry the show! First bit of news by him is that there's a new [Raspberry Pi](https://www.raspberrypi.org/) out, this time the [Raspberry Pi 3 Model B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/). Updated features include a 1.4GHz 64-bit quad-core processor, dual-band wireless LAN, Bluetooth 4.2/BLE, faster Ethernet, and Power-over-Ethernet support (with separate PoE HAT). All for the same price as before! More information can be found on youtube [here](https://www.youtube.com/watch?v=zQZxdiz2UAs) and [here](https://www.youtube.com/watch?v=0keOYRbsvxc).

10:34 Wayne has more newsworthy-ish news in that the humble bundle has a [diy electronics books bundle](https://www.humblebundle.com/books/diy-electronics-books) and it's available for the next 11 days, so check it out!

12:31 Wayne wants to talk a little bit about people and change. The moral of the story is don't move the shutdown button!

21:22 Mark brings it back to news with two interesting articles on [insights.ubuntu.com](https://insights.ubuntu.com/): [Your first robot](https://insights.ubuntu.com/2018/03/16/your-first-robot-sharing-with-others-5-5) and [MAAS for the home](https://insights.ubuntu.com/2018/03/06/maas-for-the-home) around which the guys have a discussion.

28:03 Wayne did something really cool that he's really chuffed about! This is how he did it:
* He copied all his media files, music, training videos onto a 160G drive, plugged the drive into his server, made an image of the drive with the following commands: `lsblk` - list all block devices
* `dd if=/dev/sdc of=~/nextcloud-media.img bs=4M`
* This made an image of the drive. He also attached the img file / drive to that same vm. He then attached gparted to a cdrom in one of his vms. He set the image size using this command:
* `sudo qemu-img resize nextcloud-media.img 100G`
* He then went into his Nextcloud VM and attached the img file to the VM. He went to Nextcloud and added a local mounted location as an External Storage device in NC.

Nice..

34:17 Wayne has been doing some remote support for a small business. He's using the [Libre Office suite](https://www.libreoffice.org/) in this support and is developing a SQL database using [Base](https://www.libreoffice.org/discover/base/) and relying on the [Frugal Computer Guy's tutorials](	http://thefrugalcomputerguy.com/vtOfcSpreadsheet.php) and [Codecademy's SQL course](https://www.codecademy.com/learn/learn-sql) for help in this. Mark mentions [gnucash](https://gnucash.org/) as a possible alternative for accounting software and Wayne wonders if he should go down that road instead of reinventing the wheel.

41:41 Under the Hood - Wayne talks about a video detailing [vi mode in bash](https://www.youtube.com/watch?v=GqoJQft5R2E).

Mark tells us about an interesting blog post that he read that is no longer available online! Always good to do your research and verify your links before committing them to a podcast! :-)

45:29 Irish saying of the podcast: T&amp;aacute s&amp;eacute an-fhuar, ach t&amp;aacute s&amp;eacute tirim
