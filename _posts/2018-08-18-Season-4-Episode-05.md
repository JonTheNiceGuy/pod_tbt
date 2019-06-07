---
title: The Binary Times - Series 4 Episode 5
ogg: http://archive.org/download/thebinarytimes_S04E05_chugat/thebinarytimes_S04E05_chugat.ogg
mp3: http://archive.org/download/thebinarytimes_S04E05_chugat/thebinarytimes_S04E05_chugat.mp3 
layout: post
permalink: /series4/episode5
image: ThePodcastersS04E05.png
image_alt: The Binary Times guys are at it again
series: 4
episode: 5
post_time: "16:40:00"
---
00:24 Wayne welcomes us to Series 4 Episode 5 from a wet and muggy Bristol. Mark tells us it's a soft day in Kilkishen. Winter has finally arrived, fires and being lit, and the shop across the road from Mark has just installed an ice cream machine.

02:22 Wayne asks Mark what he's been at in his linux world for the last two weeks. Mark mentions the [recent review the guys received on Linux Links](https://www.linuxlinks.com/review-the-binary-times-podcast/) inspired Mark to improve his audio set up. At first, Mark decided to go all hardcore and install [Slackware](http://www.slackware.com/) and design his own digital studio with the help of [Slackermedia](http://slackermedia.info/). This was against Wayne's better judgement. Mark tells us it's been a long time since he installed Slackware, and the last slackware derivative distro he installed was Turbolinux (he remembered incorrectly, the distro he installed was [VectorLinux 5.8](http://www.vectorlinux.com/) and he has the discs to prove it)! Things haven't changed much in the slackware world as [LILO](https://docs.slackware.com/slackbook:booting) is still the bootloader and this and the amount of maunual setting up required prompted Mark to make an executive decision to drop Slackware for now and come back to it when he had more time, probably when he retires, though slackware might not be around then because of the [2038](https://xkcd.com/607/) bug. Mark installed [Ubuntu Studio](https://ubuntustudio.org/) instead and concentrated on setting up his audio. Mark thanks the [Ubuntu Studio development team](https://launchpad.net/~ubuntustudio-dev) for helping make all this possible.

08:10 Mark asks Wayne about his last two weeks with Linux. Wayne tells us that he has been spending more and more time with [GNS3](https://www.gns3.com/). He also tells us that he purchased a [mikrotik router](https://mikrotik.com/product/RB750r2) that comes with [RouterOS](https://mikrotik.com/software). Wayne goes on to tell us that there is a [Router OS image](https://docs.gns3.com/appliances/mikrotik-chr.html) available for GNS3, with which he's been playing around with and having some fun. He's still struggling with whether he should be playing with [pfSense](https://www.pfsense.org/) or RouterOS, all comments and feedback welcome. Mark tells us that he's waiting for his [Turris Mox](https://mox.turris.cz/en/overview/).

16:15 Wayne has been looking into the differences between CAT5e, CAT6 and CAT6A. Each cable type basically allows you to carry more information further. He used an article [from kit-communications](http://www.kit-communications.com/FAQCat5evsCat6.htm) for his information.

20:45 Wayne tells us how he saw an ad for [NordVPN](https://nordvpn.com/) on prime time TV. This leads to a discussion around privacy and how privacy concerns are becoming more mainstream.

24:02 Wayne tells us about how [coinhive malware has infected Mikrotik routers](https://nakedsecurity.sophos.com/2018/08/03/routers-turned-into-zombie-cryptojackers-is-yours-one-of-them/). This leads to a discussion around routers and patching, and the conclusion comes from the article: patch early and patch often

28:00 Wayne tells us that he's removed [Kubuntu 18.04](https://kubuntu.org/news/kubuntu-18-04-has-been-released/) from his [Thinkpad X220 laptop](https://support.lenovo.com/ie/en/solutions/pd015812) and has returned to [Ubuntu MATE 16.04](https://ubuntu-mate.org/blog/ubuntu-mate-xenial-final-release/). He's sticking with Ubuntu MATE 16.04 until end of life because it's so rock solid (you can check end of life by typing `ubuntu-support-status` at the command line). Wayne also mentions the linux links review as he will now endeavour to keep his pronouncements as accurate and up to date as possible. He was also really happy with the placing of the Binary Times in the Linux Links [Linux Podcast Scene](https://www.linuxlinks.com/review-linux-podcast-scene-movers-shakers/) article. 

33:47 Mark mentions that since upgrading to Kubuntu 18.04 he has noticed a problem with playing steam games in that they tend to crash more often. Since he's talking about Steam he mentions the news that [Valve seems to be working on tools to get Windows games working on Linux](https://arstechnica.com/gaming/2018/08/valve-seems-to-be-working-on-tools-to-get-windows-games-running-on-linux/). This brings the conversation around to whether having proprietary applications on free platforms is a good idea, before Mark quickly mentions that the "Respects Your Freedom" certification programme [continues to grow](https://www.fsf.org/blogs/licensing/respects-your-freedom-certification-program-continues-to-grow). He also mentions that the FSF is looking for a [Business Operations Manager](https://www.fsf.org/news/fsf-job-opportunity-business-operations-manager). Wayne bought his X220 in the belief that [libreboot](https://libreboot.org/docs/hardware/) would some day be available for it. Mark goes on to mention an article they both read on [how open source has failed](https://libreboot.org/docs/hardware/) and how free and open source software is being used to concentrate wealth through corporations use of it and abuse of software patents and copyright law. Mark finishes this piece with a mention of Defective by Design's [IDAD 2018 - A Day Without DRM](https://www.defectivebydesign.org/dayagainstdrm), coming up on 18 September 2018.

40:03 This podcast is dedicated to celebrating [Debian turning 25](https://bits.debian.org/2018/08/debian-is-25.html) !

40:50 Under the Hood: Wayne harps back to Ubuntu MATE for his Under the Hood. To reclaim some desktop realestate, he [removed the word 'menu'](https://ubuntu-mate.community/t/brisk-menu-and-the-word-menu-can-i-remove-it-please/14840) from the top bar and also removed the date. He did this by opening a terminal and typing the following: `gsettings set com.solus-project.brisk-menu label-visible false`.

To remove the date, right click on the time, then click preferences, then uncheck 'show the date'.

Mark's starts his Under the Hood with something that is not an under the hood but an interesting read: Neal Stephenson's ["In the Beginning was the Command Line"](http://cristal.inria.fr/~weis/info/commandline.html). His Under the Hood is from Debian's manual: "commands for reading documentation". The three commands he gives are:

* `man [section-number] subject` - a crucial command for helping you to learn how to use it and other Linux commands.
* `info [subject]` - provides hypertext like documentation in that you can jump around the documentation by following links in the text.
* `help [subject]` - provides on-line help about bash's built in commands.

47:57 Irish Saying of the Podcast: [Saol fada chugat,](https://www.youtube.com/watch?v=wFUTHcjiZGo&list=PLAqwvAKGDsHBe-8Yk3OPsLPIDnd0mSK9O) Debian, or long life to you, Debian.

We hope you enjoyed this episode as much as we did making it!