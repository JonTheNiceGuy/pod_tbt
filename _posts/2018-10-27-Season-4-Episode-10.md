---
title: The Binary Times - Series 4 Episode 10
ogg: http://archive.org/download/thebinarytimes_S04E10_cota/thebinarytimes_S04E10_cota.ogg
mp3: http://archive.org/download/thebinarytimes_S04E10_cota/thebinarytimes_S04E10_cota.mp3 
layout: post
permalink: /series4/episode10
image: ThePodcastersS04E10.png
image_alt: The Binary Times boys are back in the hot seats
series: 4
episode: 10
post_time: "17:20:00"
---
00:24 Wayne welcomes us to Series 4 Episode 10 of the Binary Times. Bristol is bright and sunny, and Mark isn't sure what time zone he's in any more. At least the day is a good day to be alive in.

01:16 Wayne asks Mark what he's been up to for the last two weeks, and Mark tells us. First he tells us that he's sporting his new [sweatshirt](https://www.hellotux.com/the_binary_times_sweatshirt) from [Gabor](https://kg.hu/) and co at [Hello Tux](https://www.hellotux.com/) and loving it. He goes on to tell us that he has installed [Elementary OS](https://elementary.io/) and he's really impressed (the release notes for Elementary OS 5 Juno can be found [here](https://medium.com/elementaryos/elementary-os-5-juno-is-here-471dfdedc7b3)). Mark notes the [Libre Office suite](https://www.libreoffice.org/) isn't installed by default so the first thing he does is install it. Mark calls out Elementary's coding editor and the file manager for special mention. He goes on to say that after first impressions he would even consider using it on laptops and for the Coding Club. Mark then talks a bit further about the Coding Club.

09:12 Mark asks Wayne what he's been at. Wayne tells us he's been going bonkers with Linux the last two weeks he's been doing so many things. He first mentions the second annual [Sonoj Convention](https://www.sonoj.org/) that's on right now. What he really likes is the fact that it can be [streamed live](https://streaming.media.ccc.de/sonoj2018) and downloaded later.

12:49 The next thing Wayne chats about is the [Raspberry Pi TV hat](https://www.raspberrypi.org/products/raspberry-pi-tv-hat/). This opens all kinds of opportunities for working with TV streams. Mark tells us that he recently got a [POE hat](https://www.raspberrypi.org/products/poe-hat/) but is unsure of its utility, while Wayne mentions that you can get a [GPIO extender](https://www.modmypi.com/raspberry-pi/gpio-and-breadboarding/26-pin-gpio-connectors/26-pin-gpio-connector-header-extender-extra-tall). Wayne lets us know that there are [tutorials](https://thepihut.com/blogs/raspberry-pi-tutorials/how-to-stream-digital-tv-with-the-raspberry-pi-tv-hat) available already for the [Raspberry Pi TV hat](https://www.raspberrypi.org/products/raspberry-pi-tv-hat/).

17:35 Wayne and Mook talk about the [Ubuntu user statistics](https://www.ubuntu.com/desktop/statistics).

22:58 Wayne tells us a bit of a convulted story about [KVMs](https://www.linux-kvm.org/page/Main_Page), [16.04](http://releases.ubuntu.com/16.04/), [18.04](http://releases.ubuntu.com/18.04/) and [OS-Ticket](https://osticket.com/). Please find the following as notes to get osticket working on Ubuntu 18.04:

* [OSTicket setup on 18.04](https://computingforgeeks.com/how-to-install-osticket-on-ubuntu-18-04-bionic-beaver/)
* The php packages require the universe repositories, this can be enabled (know this is the universal repository and not maintained by Canonical) thus: `sudo add-apt-repository universe`
* You can get [OSTicket from github](https://github.com/osTicket/osTicket/releases/download/v1.10.4/osTicket-v1.10.4.zip)
* You can get Mariadb 10.3 from [here](https://downloads.mariadb.org/mariadb/repositories/#mirror=ukfast&distro=Ubuntu&distro_release=bionic--ubuntu_bionic&version=10.3).
* You need to link the osticket.conf to nginx's default site using this command: `sudo ln -s /etc/nginx/conf.d/osticket.conf /etc/nginx/sites-enabled/default`.
* A fix for the 'Valid CRSF toke issue' can be found [here](https://github.com/osTicket/osTicket/issues/4262).
* A fix for the ajax white box issue can be found [here](https://ivan.reallusiondesign.com/osticket-nginx-config/).
* Untested WHITE BOX issue fixes can be found [here](https://www.howtoforge.com/tutorial/how-to-install-osticket-with-nginx-on-ubuntu-16-04/), [here](https://forum.osticket.com/d/85376-resolved-blank-white-box-for-all-help-popups/4) and [here](https://forum.osticket.com/d/92362-blank-white-box-when-transferring-ticket).

27:04 Wayne tried to get Office 365 working with Thunderbird without success. Speaking of failures, Mark mentions that he recently upgraded his Ubuntu Touch phone but the upgrade has left his phone fairly unresponsive and unusable unfortunately. Wayne brings the chat back to OSTicket and why he wants to use it and mentions [Zim](http://zim-wiki.org/) as an alternative. The guys talk about using OSTicket, documentation and retirement.

33:47 Wayne tells us he bravely did a do-release upgrade to his 16.04 box over SSH and the guys discuss all the new changes to 18.04.

39:20 Under The Hood - Mark tells us that there are [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface) [frontends](https://en.wikipedia.org/wiki/Graphical_user_interface) for [systemd](https://freedesktop.org/wiki/Software/systemd/). These include [systemdgenie](https://cgit.kde.org/systemdgenie.git/), [systemd-kcm](https://download.kde.org/stable/systemd-kcm/) (superceded by systemdgenie), systemd system manager and <a href="https://github.com/mmstick/systemd-manager">systemd manager</a>, as well as [cockpit](https://cockpit-project.org/). Mark found this out with the help of [Linux Magazine](http://www.linux-magazine.com/Issues/2018/214)!

Wayne's first under the hood is a vim tip - Switching case of characters - Press "~" - if you keep pressing "~" it will switch case one character at a time. See [this article](http://vim.wikia.com/wiki/Switching_case_of_characters) for more. He goes on to say using the "." repeats commands. Wayne goes on to tell us to create a simple webpage for the current working directory over port 8000, use this command: `Python -m SimpleHTTPServer`

Robert wrote in to inform us that this module seems to come standard in any installation of Python 2 but something to be aware of is that in many distros, the "python" command is symlinked to Python 3. Since Python 3 doesn't include this module in its standard library, you need to run "python2 -m SimpleHTTPServer" to use it.

46:06 Irish saying of the podcast - "Faigh do chóta agus cuir ort é" Get your coat and put it on!