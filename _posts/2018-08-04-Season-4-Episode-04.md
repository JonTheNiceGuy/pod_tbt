---
title: The Binary Times - Series 4 Episode 4
ogg: http://archive.org/download/thebinarytimes_S04E04_fluich/thebinarytimes_S04E04_fluich.ogg
mp3: http://archive.org/download/thebinarytimes_S04E04_fluich/thebinarytimes_S04E04_fluich.mp3 
layout: post
permalink: /series4/episode4
image: ThePodcastersS04E04.png
image_alt: The Binary Times podcast, back with Mark
series: 4
episode: 4
---

00:24 Series 4 Episode 4 starts with Wayne regaling us from a wet and windy Bristol, his spirits have lifted as the wind blows through his hair and the rain saturates him from head to toe. Mark is concerned that Wayne is experiencing that amount of weather while recording in his house though Wayne assures us that he is doing an outside broadcast. Mark goes on to tell us that the rain has returned to Kilkishen. The guys go on to discuss their differences in opinion on the weather.

02:04 Wayne asks Mark what he has been doing for the last while, and Mark tells us that the Kilkishen Coding Club took place with two families turning up despite the Clare / Galway Hurling match taking place at the same time. Everyone there had a good time coding in <a html="https://scratch.mit.edu/download#other">Scratch</a> and some [web design](https://www.w3schools.com/html/default.asp). Mark thanks the [Kilkishen Parent's Association](https://www.facebook.com/kilkishenparentsassociation/) for kindly renting the cultural centre for the time to allow the event to take place.

12:36 Mark's other Linuxy news is related to setting up laptops and servers for the Kilkishen Coding Club, and he tells us how he found Ubuntu Server 18.04 too different from 16.04 to allow him to be productive quickly so he reverted to using 16.04. This leads to a discussion around the differences between Ubuntu server 16.04 and 18.04.

19:51 Wayne tells us what he's been up to. He finally started to work on his [X220 Thinkpad](https://support.lenovo.com/ie/en/solutions/pd015812) laptop. He's installed Kubuntu 18.04 on it and is trying to take on the ["K" suite of software](https://www.kde.org/applications/). This provokes a discussion around embracing change and differences in desktop environments. Wayne tells us he really likes Kubuntu though it's not on his main machine and that Ubuntu MATE is still his favourite.

29:17 Wayne tells us a story about change and upgrades. He recently upgraded a kernel from 4.4 to 4.15 and hit a problem with wireless drivers. He found his solultion in the last post to a thread he found on the  [Ubuntu Forums](https://ubuntuforums.org/showthread.php?t=2395628).

30:43 Wayne decides to change topic completely and talk about his [Cisco CCNA](https://learningnetwork.cisco.com/community/certifications/ccna) and his recent purchase of a microtik router and [Microtik's RouterOS](http://www.mikrotik-routeros.net/routeros.aspx). This leads him around to talking about [GNS3](https://www.gns3.com/), a Graphical Network Simulator that does what it says on the tin. The guys recommend GNS3 as something to have a bit of fun with.

39:40 Mark talks about some listener feedback. Tom wrote in to suggest a [linuxbabe article on how to install skype](https://www.linuxbabe.com/ubuntu/install-skype-ubuntu-18-04-lts-desktop). This lead Mark to think about doing a segment on installing "essential" proprietary applications. In the meantime, [Martin Wimpress](http://wimpress.org/) wrote a [blog post on snapcraft.io](https://snapcraft.io/blog/get-productive-on-the-linux-desktop-with-7-essential-apps) detailing how to get productive on the Linux desktop with 7 essential snap apps. Mark goes on to tell us about the apps and how to snap install them.

45:20 Some more listener feedback, and this one is from Old Nerd on our Telegram group, detailing [4 simple steps to clean your Ubuntu System](https://www.debugpoint.com/2018/07/4-simple-steps-clean-ubuntu-system-linux/). This leads nicely into Under the Hood.

46:11 Under the Hood - Mark's under the hood is cleaning your apt cache. You do this by first checking the size, and you do that by typing: `du -sh /var/cache/apt/archives`

If it is large, you can clean it out by typing the following: `sudo apt-get clean`

47:38 Wayne talks about the ip route 2 suite of commands.

* `ip route` - show the ip routing table
* `ip ad` - show the ip address assigned to interfaces
* `ip ad sh eth0` - show the ip address assigned to ethernet0
* `sudo ip link set eth0 down` - take down eth0
* `sudo ip link set eth0 up` - bring back up eth0

50:40 Wayne thanks all our patrons and donors, most recently [Squid](https://steamcommunity.com/id/OSCowner) from the [Open Source Community on Steam](https://steamcommunity.com/groups/opencommunity)

51:25 Irish Saying of the podcast - "T&aacute; s&eacute; anna fluich", or it is very wet.

Thanks for listening, we hope you enjoyed the podcast as much as we did making it!
