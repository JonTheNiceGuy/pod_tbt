---
layout: post
permalink: /series1/episode7
series: 1
episode: 7
title: The Binary Times - Series 1 Episode 7
ogg: http://archive.org/download/thebinarytimes_S01E07_GoNeiri/thebinarytimes_S01E07_GoNeiri.ogg
mp3: http://archive.org/download/thebinarytimes_S01E07_GoNeiri/thebinarytimes_S01E07_GoNeiri.mp3
image: ThePodcasters7.png
image_alt: The Podcasters in full glory
post_time: "18:00:00"
---
00:24 Intro, more sunny weather, Wayne and Mark talk about the relativity of time.

01:43 Mark's been tidying his office, bought an [Asus 24" Gaming monitor](https://www.amazon.co.uk/ASUS-VS248HR-Gaming-Monitor-DVI-D/dp/B014RKZ81O) to complete his dual monitor setup and has been trying out different distros:
* [Open Suse Leap 42.2](https://software.opensuse.org/422/en), a nice responsive desktop, but encountered dependancy problems once [packman repositories](https://en.opensuse.org/Additional_package_repositories#Packman) were enabled.
* [Netrunner](http://www.netrunner.com/), a run everything out of the box using KDE and Debian experience, but found to be slow and unpleasant.
* Downloaded [Zephyr](https://sourceforge.net/projects/zephyrlinux/) but didn't do anything with it. Please note that as of 19/04/2017, Zephyr has been discontinued and is now [Crowz](https://sourceforge.net/projects/crowz/).
* [Deepin](https://www.deepin.org/en/), a Debian unstable based distro with a really nice desktop experience based on a dock and hot corners / sides.
* [Linux Mint](https://linuxmint.com/), a fantastic out of the box experience where everything works nicely. Mark's concerns around Mint's security strategy make him wonder if it is a good idea to use it as a daily driver.

06:48 This leads into a discussion around Ubuntu updates.

09:00 Mark continues his gripe against [Gnome 3](https://www.gnome.org/gnome-3/) and mentions the [OMG Ubuntu article](http://www.omgubuntu.co.uk/2017/04/petition-kde-plasma-ubuntu-desktop) petitioning Mark Shuttleworth to [make Plasma Ubuntu's Next Desktop](https://www.change.org/p/canonical-ltd-make-kde-plasma-the-default-desktop-for-ubuntu-18-04-instead-of-gnome-shell). He plans to sign it.

10:08 Mark goes on to mention the [TuxDigital](https://www.youtube.com/channel/UCmyGZ0689ODyReHw3rsKLtQ) video on [Why Ubuntu 18.04 Should Use KDE Plasma Instead of GNOME](https://www.youtube.com/watch?v=F1i7jAtHcw4) while Wayne shockingly admits he's not a KDE fan because he's into light DEs (eg. [MATE](https://mate-desktop.org/)) and the terminal.

13:07 Wayne suggests we should both try [Gnome 3](https://www.gnome.org/gnome-3/) in a VM, then realises that you have to install on hardware to get a real feel. Mark says that's what he did with [KDE Neon](https://neon.kde.org/) and tells us that [Dolphin](https://www.kde.org/applications/system/dolphin/) is the best file manager bar none.

14:41 Mark mentions [TuxDigital](https://www.youtube.com/channel/UCmyGZ0689ODyReHw3rsKLtQ) is a channel he hadn't heard of before and intends to spend more time there. Wayne's looking forward to that!

15:17 Wayne describes the wonderful world of [ssh](https://www.ssh.com/) and the authentication errors he has to put up with when setting up systems. His way around it is to type the following: `ssh -o PubkeyAthentication=no pi@[insert ip address of pi]`

19:03 Wayne goes on to say that he's continuing his messing around with raspberry pi, leds, buttons and pull down resistors and gives a shout out to the [CamJam Edukit worksheets](https://www.camjam.me/).

19:45 Wayne talks about ssh, scp and [Gigolo](https://www.pending.io/pages/software/gigolo/). To recursively copy directories with scp, use the following command: `scp -r user@your.server.example.com:/path/to/foo /home/user/Desktop/`

21:56 Wayne talks about his experience of upgrading his [Samsung Galaxy S3](https://www.samsung.com/global/galaxys3/) from cyanogen mod to [LineageOS](https://lineageos.org/). It wasn't good.

27:10 Mark tells us his [ubuntu phone](https://www.bq.com/en/support/aquaris-e4-5-ubuntu-edition/support-sheet) was ideal for him and he wonders what to do with it and his [BQ M10 tablet](https://www.bq.com/en/support/aquaris-m10-ubuntu-edition/support-sheet). For now he'll just wait and see what progress [yunit](https://yunit.io/) and the [UBports guys](https://ubports.com/) make. This leads onto a discussion on the benefits of [open hardware and firmware](http://www.markshuttleworth.com/archives/1332) and Mark calling for more movies like the [Fast and Furious 8](http://www.fastandfurious.com/) to create awareness around poorly implemented proprietary firmware, governments legislating against same and a disbandment of the WTO!

33:48 Wayne talks about something that happened a few months ago, [FOSSDEM](https://fosdem.org/2017/) and the [videos](https://video.fosdem.org/2017/) of the presentations. Mark mentions a [keynote given by Aaron Siego back in 2015 at OSC](https://www.youtube.com/watch?v=_jes7bzEZzY) in which he talks about the importance of making great free software.

36:32 This turns the conversation around to how software developers get paid making free software. [Elementary OS' App center](https://developer.elementary.io/) is mentioned as a method for getting paid, and Mark points out that [ most kernel developers are professional software developers in paid employment](https://www.linuxfoundation.org/announcements/linux-foundation-releases-development-report-highlighting-contributions-to-linux). Mark also tells us he is an associate member of the [FSF](https://my.fsf.org/join), donates to [Blender](https://www.blender.org/foundation/donation-payment/), is a lapsed supporter of [KDE](https://www.kde.org/donations) and uses [Kolabnow](https://kolabnow.com/) as his email provider. He believes the money is in the services around the software rather than the software itself. [Food for thought](http://www.thefreedictionary.com/food+for+thought).

42:03 Under the Hood - Wayne mentions the following:
* `Ctrl+U` - to delete from the position of the cursor to the beginning of the line.
* `Ctrl+R` - Recursive search, to clear the result from `Ctrl+R` use `Ctrl+G`
* Mark tells us about a really cool command that he's forgotten but has something to do with `ps -ea |grep [app that's causing problems]` to find the pid and `kill [pid]`. His notebook is buried somewhere in the office.
* Use `id` to show the active user id and `last` to show the last logins on the system
* Mark mentions `who` and Wayne trumps him with `w`. `w` tells Mark he's idling...

48:07 Irish Saying for this Podcast: [Go n-&eacute;ir&iacute; an b&oacute;thar leat](https://www.youtube.com/watch?v=18p2-m6rJ3I) (May the road rise with you)!
