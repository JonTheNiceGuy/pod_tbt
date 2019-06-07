---
series: 02
episode: 01
title: The Binary Times - Series 2 Episode 1
ogg: http://archive.org/download/thebinarytimes_S02E01_NiCeart/thebinarytimes_S02E01_NiCeart.ogg
mp3: http://archive.org/download/thebinarytimes_S02E01_NiCeart/thebinarytimes_S02E01_NiCeart.mp3
image: ThePodcastersS02E01.png
image_alt: More mugs on show - Its the binary times podcast
layout: post
permalink: /series2/episode1
post_time: "12:00:00"
---
00:24 Intro to the first episode of our second season and the guys have decided to keep the weather thing going, despite its Bristol murkiness and Kilkishen dullness.

01:17 Mark's been busy during the long break between seasons with linuxy stuff and due to some user feedback has prepared some show notes (he still hasn't shaved yet)! He's glad to know that people are listening and enjoying and getting something out of the podcast as well.

02:16 Wayne tries to tell us that's he's not been up to much linuxy type stuff though we all know he's been hacking away as per usual! The guys discuss FOSS Talk Live and Ogg Camp and the implausibility of them attending.

03:38 What have we got for today's show? Mark would like to talk about the Ubuntu Hour held in Ennis, why we should be using Free Software and how to install Ubuntu Mate.It all sounds good to Wayne.

04:08 Mark talks about the Ubuntu hour held on Independence Day, 4th July, in the West County Hotel in Ennis. A good time was had by all. One of the things they managed to do while chatting was install [Ubuntu Mate 32 bit edition](http://cdimage.ubuntu.com/ubuntu-mate/releases/17.04/release/ubuntu-mate-17.04-desktop-i386.iso). They discovered the first hurdle of changing OS and that was [changing the boot order in BIOS](https://www.lifewire.com/how-to-enter-bios-2624481).

10:18 Mark recommends [Ubuntu Mate](https://ubuntu-mate.org/) as a good distro for newcomers to start with, and recommends looking at [what is Ubuntu Mate](https://ubuntu-mate.org/what-is-ubuntu-mate/) as an explanation of what is Ubuntu Mate and why to use it.

11:28 Wayne jumps in before Mark carrys on into his next segment with some good points on his own experiences with Ubuntu Mate. He points out that Ubuntu Mate is good for new users and experienced users alike due to its versatility. The fact that people Wayne has helped migrate to using Ubuntu Mate haven't been asking loads of questions is seen by both as a good sign in the ease of use. Mark advises that another easy to use distro is [Linux Mint](https://www.linuxmint.com/).

14:47 In the first place, why use Free Software in the first place? Mark talks about the importance of Free Software to maintain your Freedom and Privacy and points to some [links](https://www.gnu.org/philosophy/philosophy.html) worth looking at. Wayne talks about his transistion to Free Software. [Ableton](https://www.ableton.com/) have no future plans to port their software to Linux and a [Free and Open Source license](https://www.gnu.org/copyleft/gpl.html). The discussion continues around the benfits of Free Software and why people continue to not break bad old habits with proprietary software and formats.

25:11 With the benefits of Free Software done with, Wayne takes the opportunity to thank our first Patron on Patreon. Thank you kind gentleman for your patronage!

26:14 Wayne asked his partner for feedback on her Ubuntu Mate experience compared to Windows. Interesting feedback followed. The convenience debate continues. Wayne remains liberated and turning heads with the car he drives. Mark's car's cheating. To sum up: Use Free and Open Source Software!

34:14 Under the Hood. Wayne starts off with a beautiful one: Shift+Page up and Shift+Page Down to scroll up and down through terminal output. Mark digresses with dmeg -h producing human readable date and time output and telling us that he changed his main desktop to [Kubuntu](https://www.kubuntu.org/).

38:09 Wayne's second under the hood tackles the ip command and [iproute2](https://wiki.linuxfoundation.org/networking/iproute2) networking utilities. He points out that netstat has been replaced with ss. Of note, netstat reads from /proc, the ss command gets information directly from kernel space, meaning ss can be faster and provides more info.

* `ss -a `(all)
* `ss -t `(tcp sockets) or ss -ta (all tcp sockets)
* `ss -u `(udp)
* `ss -w `(raw sockets)
* `ss -x `(unix domain)
* `ss -d `(dhcp)
* `ss -s `(summary of socket info)
* `ss -p `(process)
* `ss -t4, -t6  `(see ipv4 or ipv6 sockets)
* `ss -t6a `(see all ipv6 sockets)
* `ss state (established `(show all established sockets)
* `ss -t state `(tcp can be in many states, ie established, syn-sent, syn-recv, closed, close-wait, etc
* `ss -tan `(translates port service name to a number ie 22 instead of ssh)
* `ss -lt `(show listening tcp ports) or
* `ss -ltn`

If you see a *:5355 it shows that this port is listening on all interfaces on your system
If you see a 127.0.1.1:53 shows that this port is listening on 127.0.1.1

* `ss -ot `(get timer information for tcp ports)
* `ss -t dst :443 `(show all tcp socktets with a destination of 443)
* `ss -t src :22 `(show all tcp sockets with a source port of 22)
* `ss -ti dst :443 `(more information about tcp 443 destination socket)

42:17 Mark's simple but good one:
* `sudo apt install --install-recommends [package you want to install]`
* `sudo apt install --install-recommends -f [package you want to install]` forces the install of packages. Use with caution!

45:28 Wayne hands over the Irish saying to Mark who was in flying Irish form earlier, we quickly see he's kinda crashed and burned. We do get two sayings out of him because of this though: ["N&iacute; neart go cur le ch&eacute;ile"](https://www.youtube.com/watch?v=J6tACGa0oQA) - there's strength with friends ie. unity is strength and "N&iacute;l saoi gan locht" - there's not a wise man without a fault!
