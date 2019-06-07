---
layout: post
permalink: /series1/episode10
series: 1
episode: 10
title: The Binary Times - Series 1 Episode 10
ogg: http://archive.org/download/thebinarytimes_S01E10_Gomaith/thebinarytimes_S01E10_Gomaith.ogg
mp3: http://archive.org/download/thebinarytimes_S01E10_Gomaith/thebinarytimes_S01E10_Gomaith.mp3 
image: ThePodcasters10.png
image_alt: The Podcasters in full glory
post_time: "12:00:00"
---
00:24 Intro to our tenth episode, or should that be our 1010 episode?! Weather is a mixed bag, and Wayne's been busy

01:56 Item One on Wayne's list: more fun with [ssh](https://www.openssh.com/) and [nginx acting as a reverse proxy](https://www.nginx.com/resources/admin-guide/reverse-proxy/), while [filezilla](https://filezilla-project.org/) doesn't feel like fun at all! Mark concludes that a [restart](https://xkcd.com/1495/) is the quickest way to cure all evils.

07:16 Wayne's discovered VMs are amazing, and that a simple command to reconfigure a keyboard from the command line is `sudo dpkg-reconfigure keyboard-configuration`

08:25 Mark's been doing a bit of keyboard work himself, and passes on this gem: when you want to turn the LED lights on in your daughter's new [CIT Storm keyboard](https://www.amazon.co.uk/CiT-Storm-Green-Front-Keyboard/dp/B01LFGOLT8/ref=cm_cd_al_qh_dp_i), type `xset led on` in the terminal, which he will probably set to come on at startup, as the keys are hard to make out without the led backlighting. As an aside Mark tells us that his son is now back to using [Windows 10](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewiso), and yes, he did make him sit down and read the [Insider Windows 10 EULA](https://insider.windows.com/Home/TermsOfUse), which he was ok with...

11:42 What else has Wayne been up to? Wayne's been web trawling and came across these handy [basic security tips](https://wiki.ubuntu.com/BasicSecurity). The article concludes with the pronouncement that the greatest security risk generally lies between the keyboard and the chair, with which they both agree and come up with seperate TLAs, Wayne's being [PICNIC](https://www.computerhope.com/jargon/p/picnic.htm) while Mark's is [PEBKAC](https://www.computerhope.com/jargon/p/pebkac.htm) (which Mark wrongly remembers as ILBKAC while he continually pronounces it as IBDIC, probably mixed memories of [EBCDIC!](http://www.webopedia.com/TERM/E/EBCDIC.html)

14:03 Wayne reports in on his CEO's experience with [Ubuntu MATE](https://ubuntu-mate.org/) on the Toshiba Satellite and HP mini - All good! Wayne argues this is good for the environement while Mark counter argues against older tech as it is not as power efficient so using older tech saves on recycling (good) but uses more power (bad). Mark talks about the [real price of cheap electronics](https://www.youtube.com/watch?v=ns-kJ5Podjw&index=17&list=LLRpY6tdhjpTkgkRsGZJA8_w) and how [we're not doing things the right way](https://www.youtube.com/watch?v=5scez5dqtAc). The conversation diverges from tech talk altogether as all things green become the topic until the guys decide to pull it back to tech. Before that happens, Mark mentions the [pending apocalypse](https://www.nasa.gov/image-feature/rift-in-antarcticas-larsen-c-ice-shelf) and they both agree [tech may save us](https://www.techwillsaveus.com/) from our destruction.

20:44 Wayne brings it back - he tells us about [GIMP save for web](https://github.com/auris/gimp-save-for-web) plugin (there's also a [deb package](http://www.getdeb.net/app/GIMP+%22Save+for+Web%22+plugin)). Mark loves the [GIMP](https://www.gimp.org/) but hates the name, it's one of those indispensable graphics manipulation tools along with [inkscape](https://inkscape.org/en/) and [krita](https://krita.org/en/). Mark then talks about the benefits of relying on donations compared to crowdfunding. Mark's used inkscape to create safety posters, and [Libre Office Draw](https://www.libreoffice.org/discover/draw/) to modify pdfs.

27:08 Wayne moves the conversation onto [Snap packages](https://snapcraft.io/). Key points he's picked up:

* Snap packages provide you with the latest version of the software. (`sudo snap refresh [package name]` - upgrades a package to its latest version)
* Snap packages do not have root access to the entire system.
* With Snaps you dont have to worry about dependencies.
* Removing a Snap package doesnt leave a lot of crap behind.
* Developers can use an application called [snapcraft](https://build.snapcraft.io/) to turn their applications into a snap.

Mark thinks it'll be a good thing for Distros if Snaps take off as it will allow Distro maintainers to concentrate on core distro stuff rather than packaging loads of applications. Mark goes on to mention Mark Shuttleworth's Youtube video [apt-get and docker had a baby](https://www.youtube.com/watch?v=0z3yusiCOCk).

35:19 Wayne sneakily moves on to Under The Hood.

* `snap find` : To list the available packages (only shows promoted and public snaps)

To list all snaps:
* `snap install uappexplorer-cli`
* `uappexplorer-cli --type snap`

Other commands include:
* `sudo snap install [package name]` : To install a package
* `sudo snap list` : To view all the installed snap packages
* `sudo snap changes` : To view a list of logged actions
* `sudo snap refresh [package name]` : To upgrade a package to its latest version
* `sudo snap refresh hello --beta` : If you know there is a beta version available
* `sudo snap revert` : To rollback to previous versions
* `sudo snap remove` : To uninstall a package

The commands can be found in [this Joe Collins Video - An introduction to Snap packages for linux](https://www.youtube.com/watch?v=j40tNL3t4gw)

Wayne finishes his key points with the following:
* A snap is a squashfs, Read Only, bind-mounted in /snap/[snap_name]/[version]
* Each time you upgrade a snap, a new version directory is created
* Snap Apps processes are isolated from each other and isolated from the system

43:06 Mark asks Wayne what network commands he uses, he's fishing for ifconfig and ip. Time is running long though, so he's going to leave describing the differences til the next podcast.

46:04 Time for the Humble Bundle Book Bundle Shoutout, this time it's for the [Linux & Open Source Humble Book Bundle](https://www.humblebundle.com/books/linux-book-bundle), including loadsa goodies like Pro Vim and others.

49:24 Irish saying for the podcast is ["T&aacute; m&eacute; go maith, go raibh maith agat, agus t&uacute; f&eacute;in"](https://www.youtube.com/watch?v=TNU0b1nhpzY) (I'm well, thanks for asking, and you?)