---
title: The Binary Times - Series 2 Episode 9
ogg: http://archive.org/download/thebinarytimes_S02E09_Samhain/thebinarytimes_S02E09_Samhain.ogg
mp3: http://archive.org/download/thebinarytimes_S02E09_Samhain/thebinarytimes_S02E09_Samhain.mp3 
layout: post
permalink: /series/episode
image: ThePodcastersS02E09.png
image_alt: Marks new office
series: 02
episode: 09
---
00:24 Wayne welcomes us to the long awaited Bumper Edition of Season 2 Episode 9 of the Binary Times, it's something to look forward to! Between Halloween and the recent release of Ubuntu and flavours 17.10, there's a lot to talk about!

02:01 Mark tells us that he's been busy at work and moving his home office, so finally there'll be no more talk of tidying the office (we hope!)

02:44 Wayne's been doing quite a bit in the Linux world, so much he's not sure where to start! [vifm](https://vifm.info/) gets first mention, which Wayne likens to [midnight commander](https://midnight-commander.org/). Mark thinks he'll stick with midnight commander, but may give vifm a go. Wayne likes vifm over midnight commander because of the vi keybindings. Some links to go with this piece:
* [vifm info on tecmint](https://www.tecmint.com/vifm-commandline-based-file-manager-for-linux/0)
* [vifm manual](https://vifm.info/manual.shtml#Visual%20Mode)
* [vifm colours](https://github.com/vifm/vifm-colors)
* [vifm quick start tutorial](https://wiki.vifm.info/index.php?title=Quickstart_Tutorial)

Useful Keys

* `ga` - calculate the current highlighted directory size
* `zo` - show dot files
* `zm` - hide dot files
* `e` - explore selected file in current pane
* `cW` - Rename file (but not extension)
* `cw` - Rename entire file
* `dd` - Delete selected file
* `p` - copy deleted file in current location
* `P` - Move deleted file in current location

09:49 Wayne reads out some feedback from our listeners, this one from Maurizio about dd and progress status. Type the following to see the progress of the dd command: `dd if=/dev/random of=/dev/null count=1M status=progress`

As well as this excellent advice, you can use the [pv](https://linux.die.net/man/1/pv) (pipe viewer?) command to achieve the same effect, a simple example of using pv is as follows: `head -c 1M /dev/random | pv > /dev/null`

12:58 Wayne tells us about a "new" firefox plugin called [vimfx](https://github.com/akhodakivskiy/VimFx), a legacy [firefox plugin](https://addons.mozilla.org/en-US/firefox/addon/vimfx/). It provides you with vim keybindings within Firefox. Links to addons compatible with firefox 57+ are given in the previous link. Wayne goes on to tell us that [firebug](https://addons.mozilla.org/en-US/firefox/addon/firebug/) has been replaced by [firefox's built in developer tools](https://developer.mozilla.org/en-US/docs/Tools). Mark wishes that citrix integration will be coming to Firefox... links for citrix are as follows:
* [Citrix receiver for Linux](https://www.citrix.com/downloads/citrix-receiver/linux/receiver-for-linux-latest.html)
* [Citrix Ubuntu Community Help Wiki](https://help.ubuntu.com/community/CitrixICAClientHowTo)

20:12 Waynes reveals that he is no longer using [duckduckgo](https://duckduckgo.com/) and is now using [startpage](https://www.startpage.com/), labelled as "the world's most private search engine". Mark thinks [Yahoo may have been acquired by Verizon](https://www.verizon.com/about/news/verizon-completes-yahoo-acquisition-creating-diverse-house-50-brands-under-new-oath-subsidiary).

26:12 The guys talk about the 17.10 release of the various flavours of Ubuntu, namely [Ubuntu 17.10](https://www.ubuntu.com/desktop/1710), [Kubuntu 17.10](https://kubuntu.org/news/kubuntu-17-10-artful-aardvark-is-released/) and [Ubuntu MATE 17.10](https://ubuntu-mate.org/blog/ubuntu-mate-artful-final-release/). In the totally off topic section Mark mentions that he might try a new release of [Chakra OS](https://chakralinux.org/?about) to replace Ubuntu on his Thinkpad.

50:35 Under the hood, Wayne says vifm is his under the hood, Mark mentions that rysnc has a progress option, --progress

51:47 Irish saying of the podcast is "O&iacute;che Samhain ar fud an domhain" Halloween night around the world.
