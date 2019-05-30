---
layout: post
permalink: /series1/episode12
series: 1
episode: 12
title: The Binary Times - Series 1 Episode 12
ogg: http://archive.org/download/thebinarytimes_S01E12_SlanGoFoill/thebinarytimes_S01E12_SlanGoFoill.ogg
mp3: http://archive.org/download/thebinarytimes_S01E12_SlanGoFoill/thebinarytimes_S01E12_SlanGoFoill.mp3 
image: ThePodcasters12.png
image_alt: Its back to the Ubuntu mug
---
00:24 Intro to the final episode of Season One, where the guys managed to talk about not talking about the weather!

01:22 Mark talks about doing linuxy type stuff. He has an old PC with an Intel Core 2 Duo with 2GB RAM and a 120GB hard drive running ubuntu and unity. Unity is quite slow and unresponsive on it so he started up a command line interface with ctrl alt F2 and typed in ` sudo apt remove unity*` followed by `sudo apt install plasma-desktop` and finally after looking up what to do, typed `sudo apt install kubuntu-desktop`. He also had to enable the kubuntu backports to get the 5.8 LTS version of the KDE desktop, which he thought was a bit strange. He did this with the following commands:
* `sudo add-apt-repository ppa:kubuntu-ppa/backports`
* `sudo apt update && sudo apt dist-upgrade`

He's loving his kubuntu desktop and once he's tested it a bit more plans to move his main desktop over to it.

Mark goes on to tell us that he has installed [Chakra os](https://chakralinux.org/) and it's nice and KDE isn't as heavy as people think.

08:34 Mark goes on to tell us about [KDE-neon](https://neon.kde.org/) and [KDE](https://www.kde.org/products) in general in his own inimical style. He suggests looking up the sites to get a better explanation.

10:49 Mark announces that due to feedback on the show he's organised an Ubuntu Hour on the 4th of July, independence day, at the [West County Hotel](https://www.openstreetmap.org/search?query=west%20county%20hotel%20ennis#map=19/52.83123/-8.98092) in [Ennis](https://www.openstreetmap.org/search?query=ennis#map=12/52.8435/-8.9970). Mark also wants to play with [Ubuntu Mate](https://ubuntu-mate.org/download/) over the weekend in preparation for the Ubuntu Hour.

11:37 Wayne tells us that he uses [Ubuntu Mate](https://ubuntu-mate.org/) but has also tried [Gnome 3](https://www.gnome.org/) though not successfully.

14:52 The conversation veers towards Wayne's CEO's experience with [Ubuntu Mate](https://ubuntu-mate.org/) and how Wayne is trying to convince him to choose [GIMP](https://www.gimp.org/) over [Photoshop](https://www.adobe.com/ie/products/photoshop.html). The conversation starts to go down the rabbit hole as Wayne and Mark discuss the pros and cons of proprietary software and formats.

21:31 Wayne pulls it back by announcing that [Skype 4.3 for Linux is no longer supported from today](https://www.skype.com/en/download-skype/skype-for-computer/) (1st July). He suggests that you should upgrade to [Skype beta](https://www.skype.com/en/download-skype/skype-for-computer/). you can do this with the following commands:
* `dpkg --get-selections | grep 'skype'` - output is `skype-bin:i386`
* `sudo apt-get --purge remove skype-bin:i386`

Wayne also suggests using Ctrl - to zoom out in Skype.

24:17 Mark advises people should start using [Wire](https://wire.com/en/).

25:15 Wayne talks about his interest in Electronics and how he has enhanced the [Rod of Doom](https://nc.fortlands.net:444/index.php/s/RiagCM5mXWE9Con). He also talks about [Ben Eater](https://eater.net) and how he built an 8 bit computer. Mark mentions the [keyboardio](https://shop.keyboard.io) but doesn't think he'll be getting one because of the steep price tag.

28:52 Wayne responds to some feedback with advice on how to [install linux on a mac](http://www.macworld.co.uk/how-to/mac/how-install-linux-on-mac-3637265).

31:21 Under the Hood. Mark talks about [KDevelop 5.1](https://www.kdevelop.org/news/kdevelop-510-released), which has vim key bindings.

32:31 Wayne talks about using lynx with vi key bindings. To get it working you need to do the following:
1. `lynx https://thebinarytimes.net`
1. press o for options.
1. press the down arrow 14 times, or until you land on 'VI keys'
1. press the right arrow, then down arrow, then right arrow again (to switch on 'VI keys').
1. press the right arrow 11 times, or until you get to 'save options to disk'
1. press right arrow key to put an X in the box there.
1. press the up arrow key 3 times, or until you get to 'save changes' and press enter.
1. lynx will always open up in VI mode from now on.

34:20 Wayne talks about [Samba and setting up network shares](https://help.ubuntu.com/community/How%20to%20Create%20a%20Network%20Share%20Via%20Samba%20Via%20CLI%20(Command-line%20interface/Linux%20Terminal)%20-%20Uncomplicated,%20Simple%20and%20Brief%20Way!) in Ubuntu.

36:50 The guys discuss the highlights of their first season.

40:06 Mark moves the conversation onto [UBPorts](https://ubports.com/) and tells Wayne that there is an image available for the [Samsung Galaxy S3](https://ubports.com/page/fs-flash-phone).The conversation moves onto apps and [uappexplorer](https://uappexplorer.com/) and the [openstore](https://open.uappexplorer.com/).

Irish Saying to end Season One: [Sl&aacute;n go f&oacute;ill](https://www.youtube.com/watch?v=Lzxhx0q99PA)!
