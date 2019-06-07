---
title: The Binary Times - Series 3 Episode 8
ogg: http://archive.org/download/thebinarytimes_S03E08_mall/thebinarytimes_S03E08_mall.ogg
mp3: http://archive.org/download/thebinarytimes_S03E08_mall/thebinarytimes_S03E08_mall.mp3 
layout: post
permalink: /series3/episode8
image: ThePodcastersS03E08.png
image_alt: Here we go again
series: 03
episode: 08
post_time: "10:45:00"
---		
00:24 Wayne welcomes us to Series 3 Episode 8 from a lovely and sunny Spring morning in Bristol. Mark remarks that it is over-cast in Kilkishen but hopes that Spring may be on the way, one day...

01:34 Mark tells us that he has been crazy, crazy, crazy busy at work! He goes on to tell us that in an attempt to improve his audio quality he has purchased a [Focusrite 2i2 Studio 2nd Gen](https://store.focusrite.com/en-gb/product/scarlett-2i2-studio-2nd-gen/MOSC0020~MOSC0020). Set up problems on his alienware PC lead him to go back to using his [Linux Mint 18.3 box](https://linuxmint.com/), so kudos to the [Linux Mint team](https://linuxmint.com/teams.php). This leads to a general discussion around general purpose computing and how amazing it is when you get it to work! Mark finally recommends the focusrite studio.

07:24 Wayne asks Mark if there's any other linuxy stuff going on in his life and Mark admits to purchasing a [Raspberry Pi 3 model B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/) which he received Thursday but he hasn't done anything with it yet.

07:59 Using this information as a segway to some news, Wayne goes on to tell us about the [Rock64 Media Board Computer](https://www.pine64.org/?product=rock64-media-board-computer), a pretty amazing bit of kit with some pretty impressive specs starting at $24. The fact that you can use Yocto brings Mark's mind back to an article he read in [Linux Magazine](http://www.linux-magazine.com/) about [building a Yocto-based Knoppix for the Raspberry Pi](http://www.linux-magazine.com/Issues/2017/200/Professor-Knopper-s-Lab-Yocto-Knoppix). Apologies to [Klaus Knopper](http://knopper.net/knopper/index-en.html) for mis-remembering his name</a>. Mark goes on to tell us about some of the boot time woes he's been having with a Dell laptop.

16:42 Wayne tells us about some issues he's been having at work with [Remmina](https://www.remmina.org/wp/) installed [as a snap](https://github.com/FreeRDP/Remmina/wiki). He resolved these issues with the following commands:
* `sudo snap connect remmina:avahi-observe :avahi-observe`
* `sudo snap connect remmina:cups-control :cups-control`
* `sudo snap connect remmina:password-manager-service :password-manager-service`
* `sudo snap connect remmina:mount-observe :mount-observe`

18:33 Wayne got a weird error on his Ubuntu MATE 17.10 machine at work and it was when he tried to change his password he got the following error messages:
```
/var/cache/cracklib/cracklib_dict.pwd: No such file or directory
BAD PASSWORD: The password fails the dictionary check - error loading dictionary
```
which was fixed with the following: `sudo apt-get install cracklib-runtime`
Wayne found this out from an [article on Ask Ubuntu](https://askubuntu.com/questions/557771/file-cracklib-dict-pwd-not-found-when-creating-a-new-user-or-changing-his-passwo).

23:38 Mark brings the conversation around to an [article on OMGUbuntu ](https://www.omgubuntu.co.uk/2018/04/enable-live-patch-kernel-updates-in-ubuntu-18-04)related to [Canonical's Live Kernel Patching service](https://www.ubuntu.com/server/livepatch). This leads to a conversation around the pros and cons of the service and Wayne's explanation of his work-life balance. Mark tells us that in [Kubuntu 18.04](https://kubuntu.org/news/kubuntu-bionic-beaver-18-04-lts-beta-2-released/) you can install the snap backend via discover but then you have to do the rest via command line rather than the gui method that's available in [Ubuntu](https://www.ubuntu.com/).

29:10 Wayne asks Mark how far are we from the [release of Ubuntu 18.04](https://wiki.ubuntu.com/BionicBeaver/ReleaseSchedule) and Mark says that it is due Thursday the 26th April, which for Mark brings to mind the [Dublin Linux Users Group's](https://www.dublinlinux.org/) amazing [meetup in Amazon](https://www.meetup.com/Dublin-Linux-User-Group/events/248227051/) where some Amazon staffers and Dublin Linux Group community members will talk about AWS and any other topics on the night. Sounds like fun though Mark won't be able to make it himself. He goes on to mention [Dublin Linux Users Group's web page](https://www.dublinlinux.org/) as a good place to check out for [free software alternatives](https://www.dublinlinux.org/free-software/) as well as [Google alternatives](https://www.dublinlinux.org/google-alternatives/). The guys discuss various search engines.

33:46 Since it's something that's being discussed in other podcasts, Wayne chats briefly about [Firefox Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/) and promises to report back on results.

36:06 Mark confesses to not listening to podcasts recently, instead he's been listening to Naomi Klein's [This changes everything](https://thischangeseverything.org/) and [The Great Courses The Science of Energy and Resources Explained](https://www.thegreatcourses.com/courses/the-science-of-energy-resources-and-power-explained.html). He's looking forward to listening to podcasts again soon.

37:11 Under the Hood - Mark continues the theme from last week by suggesting listeners try the [8-day data detox](https://datadetox.myshadow.org/detox). This leads to a conversation around data detoxification.
Wayne's under the hood is how to fix locked files in NextCloud 13. You do this like so:
* `cd /var/www/nextcloud/config`
* `vi config.php`
* Find the line that says 'maintenance' => false; and change it to 'maintenace' => true;
* Now restart the server. Once back at the command line: `sudo mysql -u root -p`
* input database root password and server password, then connect nextcloud (nextcloud is the name of the database from config.php file)
* `DELETE FROM oc_file_locks WHERE 1;`
* when finished, type `\q`
* `vi /var/www/nextcloud/config/config.php`
* change 'maintenance' => false; save and quit
* Reboot the server, you're done!

Irish saying of the podcast "T&aacute; t&uacute; mall inniu" or "You're late today".
