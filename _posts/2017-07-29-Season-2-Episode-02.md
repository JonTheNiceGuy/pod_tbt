---
series: 02
episode: 02
title: The Binary Times - Series 2 Episode 2
ogg: http://archive.org/download/thebinarytimes_S02E02_Ante/thebinarytimes_S02E02_Ante.ogg
mp3: http://archive.org/download/thebinarytimes_S02E02_Ante/thebinarytimes_S02E02_Ante.mp3 
image: ThePodcastersS02E02.png
image_alt: More mugs on show - Its the binary times podcast
layout: post
permalink: /series2/episode2
post_time: "12:00:00"
---

00:24 Intro to Series 2 Episode 2 finds Mark congratulating Wayne on a great start and our podcasters are living in dull and murky places. The guys really get into their weather!

01:45 Mark's installed [Ubuntu Mate 17.04 64 bit](https://ubuntu-mate.org/download/) on a 3GB RAM Core 2 Duo which didn't recognise [True OS](https://www.trueos.org/) as a valid operating system and completed a course in [Cisco Unified Communications Manager](http://www.cisco.com/c/en/us/products/unified-communications/unified-communications-manager-callmanager/index.html). He tells us that CUCM sits on top of a modified [Red hat enterprise linux](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) and that administration of the system is achieved through modifying options in webpages made by different factions in Cisco. He tells us of, in his opinion, the superiority of the [MX-One](http://www.mitel.com/products/unified-communications/mivoice-mx-one) and the ability to administer the system from the command line.

08:40 Wayne has been doing alot of modular sysnthesis, which can be described as using specialized software modules in various ways to modify or process a parameter of an audio signal such as, for example, the frequency or ampiltude. Wayne admits to using [Ableton](https://www.ableton.com/) to achieve this, and this leads to a conversation on building things in Open Source and [the difference between ideas people and doers](https://dannybrown.me/2011/04/29/the-difference-between-ideas-and-doing/) and the concept of [inspiration vs. perspiration](http://www.phrases.org.uk/meanings/genius-is-one-percent-perspiration-ninety-nine-percent-perspiration.html).

14:49 Mark mentions that [Sysadmin's day](https://www.youtube.com/watch?v=cfUSjgL7lwk) (28th July) was his last day at work til September as he is taking some work / life balance leave for himself to learn some [Blender](https://www.blender.org/), [Python](https://www.python.org/), [Kali](https://www.kali.org/), [Squid Proxy server](http://www.squid-cache.org/), read some books while also doing some cool stuff with the kids using [Khanacademy](https://www.khanacademy.org/). Maybe relax a bit too.

18:00 Wayne introduces our New Section, "So you've installed Ubuntu Mate, now what?" The guys talk about a few things that you do once you've installed Ubuntu Mate. [The Welcome screen](https://launchpad.net/ubuntu/+source/ubuntu-mate-welcome) gets first mention, and how easy it makes Ubuntu Mate for new users to use. Getting started is the first place you would want to go to in the Welcoms screen, and the guys discuss the various options within. Mark mentions enabling DRM in firefox too (Menu / Preferences/Content/Play DRM content). Wayne goes on to say that you can start a terminal using `CTRL-ALT-T` and typing `sudo apt update && sudo apt upgrade</span> OR `sudo apt dist-upgrade` ([the difference between the two can be found here](https://askubuntu.com/questions/81585/what-is-dist-upgrade-and-why-does-it-upgrade-more-than-upgrade#81594)). Wayne finishes the section with a discussion on [synapse](https://launchpad.net/synapse-project), when once installed is a handy utility invoked by hitting `CTRL-SPACE` which allows you to search for installed applications simply by typing the name. Synapse is one of the [must have apps/packages for new Ubuntu Mate installations](https://ubuntu-mate.community/t/some-must-have-apps-packages-for-new-ubuntu-mate-installations/756). To finally finish Mark mentions the [software boutique](https://github.com/ubuntu-mate/software-boutique/) and admires how it is laid out.

36:00 Mark goes on to tell us all that [Ubuntu 16.10 is no longer supported](http://fridge.ubuntu.com/2017/07/20/ubuntu-16-10-yakkety-yak-end-of-life-reached-on-july-20-2017/), advises that a link will be available in the show notes on [how to upgrade to 17.04](https://help.ubuntu.com/community/ZestyUpgrades) and introduces Under the Hood with the following command which will tell you the date when your system is no longer supported: `ubuntu-support-status`

38:30 Wayne talks about two things for Under the Hood:
Using Grub 2 to change which OS is the default to boot into:
1. `sudo cp /etc/default/grub /etc/default/grub.bak`
1. `sudo vim /etc/default/grub`
1. `GRUB_DEFAULT=0` - (change this to entry you want to default boot ie 5 = sixth entry)

Second Under the hood, from [Going Linux](http://goinglinux.com/shownotes.html#glp327) podcast, episode #327:
* `inxi -F`
* `inxi -Frmxx`

Mark follows up with another grub trick and that is to [turn off the quiet splash in grub](https://askubuntu.com/questions/33416/how-do-i-disable-the-boot-splash-screen-and-only-show-kernel-and-boot-text-inst#33420).

45:38 Irish saying of the podcast, [An t&eacute; nach bhfuil l&aacute;idir, n&iacute; fol&aacute;ir d&oacute; bheith glic](http://www.daltai.com/proverbs/relationships-dealing-with-others/an-te-nach-bhfuil-laidir-ni-folair-do-a-bheith-glic/), or he who is not strong must be clever, a fitting [Sysadmin Day's](http://sysadminday.com/) quote. 
