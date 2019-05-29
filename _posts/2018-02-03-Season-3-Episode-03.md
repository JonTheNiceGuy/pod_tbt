---
title: The Binary Times - Series 3 Episode 3
ogg: http://archive.org/download/thebinarytimes_S03E03_Thoil/thebinarytimes_S03E03_Thoil.ogg
mp3: http://archive.org/download/thebinarytimes_S03E03_Thoil/thebinarytimes_S03E03_Thoil.mp3 
layout: post
permalink: /series3/episode3
image: ThePodcastersS03E03.png
image_alt: Here we go again, its Mark and Wayne.
series: 03
episode: 03
---
00:24 Wayne welcomes us to the third episode of Season Three! Bristol is crowdy and cloudy and a little bit cold, while Kilkishen is nice and Springy!

01:51 Mark tells us that he's been busy commissioning new voice systems and decommissioning old pabxs. It's a bit sad but not so bad. He wonders why his comm rooms are so tidy and he can't manage the same with the office! All the same, Mark tells us he's making progress on his office tidy up and ponders what books the library decided to take. With all this going on he's not had much time for linuxy stuff.

06:03 Wayne feels the same way and is slightly irked by this. He's been looking to get into [freeipa](https://www.freeipa.org/page/Main_Page) but hit some problems so he's backing away from this at the moment. Meanwhile work is looking for him to get on top of his Windows Server knowledge so he's knee deep in Windows Server stuff at the moment. Wayne seems to admire the ease of use of Windows Server...

09:19 Wayne gets onto his linux talk! He experienced a pretty drastic bug using [Virtual Box](https://www.virtualbox.org/) that he resolved by uninstaling and reinstalling Virtual Box. He also updated [Ubuntu 16.04](http://releases.ubuntu.com/16.04/) to [17.10](http://releases.ubuntu.com/17.10/) using the following technique:

* Open 'Software &amp; Updates' using the Unity Dash
* Select the 'Updates' tab
* Find the section titled 'Notify me of a new Ubuntu version'
* Change this from 'For long-term support versions' to 'For any new version'
* Click 'Close'
* You will then be prompted to upgrade to a new version

Mark queries Wayne as to whether either Xorg or Wayland is used by default in an upgraded 17.10 and goes on to say that [Xorg will be the default for 18.04](https://insights.ubuntu.com/2018/01/26/bionic-beaver-18-04-lts-to-use-xorg-by-default/). Mark goes on to ask Wayne the benfits of using [Virtual Box](https://www.virtualbox.org/) over [Virtual Machine Manager](https://virt-manager.org/). Wayne's answers prompt Mark to reminisce once more about the PABXs he's been retiring, this time saying how long he was able to get out of learning a set of commands. Wayne applauds this.

24:30 News for us (which is actually pretty recent news for once)! Wayne tells us of the announcment of the [release of Libre Office 6](http://www.omgubuntu.co.uk/2018/01/libreoffice-6-0-release-download). Mark hadn't heard this news and notes from the [Libre Office](https://www.libreoffice.org/) website that it was announced on the 31st January. Wayne also gives us a tip on how to remove links from web addresses in Libre Office documents and that is as follows: go to Tools - Autocorrect Options then 'Options' taband uncheck 'URL recognition'. Mark and Wayne agree that they prefer to use Libre Office over Microsoft Office.

30:40 Wayne prompts Mark to thank one of our listeners for his generous gift of memory for a laptop that Mark has. Mark duly goes on to thank Paul while also noting that since he installed the RAM his boot time has come way down. He also notes that his [Linux Mint](https://linuxmint.com/) desktop starts the fastest of all his machines which is suprising as it should not be the quickest so he's putting it down to Linux Mint. Wayne mentions Joe Collins is an [advocate for Linux Mint](https://www.youtube.com/watch?v=JE4SwkJ0Fys) while Mark mentions Steven Vaughan Nichols as a [fan of Linux Mint](http://www.zdnet.com/article/mint-18-3-the-best-linux-desktop-takes-big-steps-forward/) and also mentions that he is a guest speaker in a new podcast called [command line heroes](https://www.redhat.com/en/command-line-heroes).

34:54 Mark mentions that [FOSDEM](https://fosdem.org/2018/) is now on. Wayne goes on to say that [OggCamp](http://oggcamp.org/) is scheduled for August in Sheffield. Wayne says he'd love to go so Mark says he'll go too. Mark also mentions the [Freenode conference](https://freenode.live/) as one to go to.

36:50 Under the Hood! Wayne talks about removing old kernels in CentOS. You can do this as follows (run as root): 
* `rpm -q kernel`        (lists installed kernels)
* `yum install yum-utils`
* `package-cleanup --oldkernels --count=2`

Mark looks up how to do this in Ubuntu and came up with [this](http://ubuntuhandbook.org/index.php/2016/05/remove-old-kernels-ubuntu-16-04/):

Run command to check out current kernel and DON'T REMOVE it: `uname -r`

List all kernels excluding the current booted: `dpkg -l | tail -n +6 | grep -E 'linux-image-[0-9]+' | grep -Fv $(uname -r)`

There will be three possible status types in the listed kernel images:
* `rc`: means it has already been removed.
* `ii`: means installed, eligible for removal.
* `iU`: DON'T REMOVE. It means not installed, but queued for install in apt.

To remove old kernel images with "ii" status, type: `sudo dpkg --purge linux-image-4.4.0-18-generic`

[Riveting listening!!!](https://www.youtube.com/watch?v=nGA-GCq7JWM)

44:17 Irish saying of the podcast: [M&aacute;s &eacute; do thoil &eacute;](https://www.youtube.com/watch?v=Z-K3DfkbTb8)
