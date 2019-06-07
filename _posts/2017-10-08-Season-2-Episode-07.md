---
title: The Binary Times - Series 2 Episode 7
ogg: http://archive.org/download/thebinarytimes_S02E07_reidh/thebinarytimes_S02E07_reidh.ogg
mp3: http://archive.org/download/thebinarytimes_S02E07_reidh/thebinarytimes_S02E07_reidh.mp3 
layout: post
permalink: /series2/episode7
image: ThePodcastersS02E07.png
image_alt: Its all at different angles
series: 02
episode: 07
post_time: "18:00:00"
---
00:24 Wayne welcomes us to Season 2 Episode 7 of the binary times with the news that it's slightly misty in Bristol (register mistybristol now!) while Mark informs us that it's slightly more than misty in Kilkishen. It's that time of year, you can expect another six months of this kind of chat at least!

01:34 Mark tells us that he's finally managed to break his desktop PC OS as well as finding [Ubuntu 17.10's](http://cdimage.ubuntu.com/daily-live/current/) gnome interface slightly frustrating. Wayne tells us he sticks with one distro to avoid re-learning and has shelved [Ansible](https://www.ansible.com/) at the moment for much the same reason. Mark goes on to tell us about some exciting events at the Ubuntu Hour in Ennis.

05:10 Wayne tells us he's been tinkering away, researching command line bits and bobs and being inspired by [Bryan Lunduke's](https://vid.me/BryanLunduke) minimalist inclinations.

06:26 Wayne brings us onto our "So you've installed Ubuntu MATE, now what?" section by describing a new user's experiences including queries regarding how to change settings and where to find these settings, as well as updating the system and liking [Libre Office](https://www.libreoffice.org/) over [Microsoft Office](https://products.office.com/en-ie/home) and the "always on top" feature. Mark and Wayne do a quick battle of the desktops with no clear winner. Wayne finishes by pondering the futility of the naming the calculator [galculator](http://galculator.mnim.org/) in [Ubuntu MATE](https://ubuntu-mate.org/) and the unnecessary difficulty that will give to new users but surmises that other than that the changeover to linux has been a huge success. Wayne goes onto mention that his boss bought his son a Windows PC for college and Mark mentions how his son prefers [Windows for gaming](https://www.microsoft.com/en-us/windows/windows-10-games).

17:51 Mark reveals the shocking news that [he won't have fibre broadband til the end of 2018](http://fibrerollout.ie/wp-content/uploads/2017/08/Rural-Exchange-Timeline-24-April-2017.pdf). Wayne reckons that'll be just in time for us to have sorted out the podcast!

18:40 Mark has some tips for everybody! The first is to listen to the [IRL podcast](https://irlpodcast.org/), an amazing podcast that Mozilla have created discussing real online issues and the future of the web. His second tip is the [EFF's Surveillance Self - Defense page](https://ssd.eff.org/en), another wonderful resource for teaching you how to have safer online communications. Wayne needs to get onto the EFF website for the [laptop stickers](https://supporters.eff.org/shop/laptop-camera-cover-set).

20:27 Wayne can use [Office 365 on Linux](https://support.office.com/en-us/article/Which-Browsers-Work-With-Office-Online-AD1303E0-A318-47AA-B409-D3A5EB44E452?ui=en-US&rs=en-US&ad=US)!

21:00 Wayne goes on to tell us that he uses [Virtualbox](https://www.virtualbox.org/) for testing images and the like and recently had some issues with [FreeNAS](http://www.freenas.org/) not having enough space when running an update. He used [vboxmanage](https://www.virtualbox.org/manual/ch08.html) to resize the virtual image like so: `vboxmanage modifyhd "FreeNas.vdi" --resize 6000` (6 GB)

See also this link to [extend disk and file systems in virtual box](https://oracle-base.com/articles/vm/virtualbox-extend-disk-and-file-system) for further information. Because the filesystem is [ZFS](http://open-zfs.org/wiki/Main_Page) it was not possible to use [gparted](https://gparted.sourceforge.io/) etc. to expand the volume into the newly created space, Wayne's looking into how to do that, using previous shownotes, aren't they great!

25:26 Wayne is looking to [upgrade his Windows](https://www.fsf.org/windows) work PC to [Ubuntu](https://www.ubuntu.com/download/desktop). He needs to figure out how this will affect the way he works. The guys then discuss the tedium of licensing and the few applications that make it difficult to go fully open source, namely [Active Directory](https://msdn.microsoft.com/en-us/library/bb742424.aspx?f=255&MSPPError=-2147217396), [RDP](https://msdn.microsoft.com/en-us/library/aa383015(v=vs.85).aspx) and the most applied application throughout histroy, [change](https://xkcd.com/1770/).

34:15 Wayne announces that we use [Wire](https://wire.com/en/) to do the podcast and that the [wire server code is now all open source](https://medium.com/@wireapp/wire-server-code-now-100-open-source-the-journey-continues-88e24164309c).

35:19 The guys figure that it's time for Under the Hood so Mark starts off with something that's not particularly under the hood, but interesting and under the hoody none the less. [Ubuntu Tutorials](https://tutorials.ubuntu.com/) is a great place to find tutorials on all aspects of installing and running ubuntu.

36:43 Wayne starts with what flows though him and that's administering linux systems: `man hier` is a handy command to explain the linux file system hierarchy.

Wayne's second under the hood tip is iotop, a simple top-like I/O monitor. To run it, simply type: `sudo iotop`

43:45 Irish saying of the podcast is ["An bhfuil t&uacute; r&eacute;idh"](https://www.youtube.com/watch?v=hnsL6GmnGbc) Are you ready. Good lead in to this one!
