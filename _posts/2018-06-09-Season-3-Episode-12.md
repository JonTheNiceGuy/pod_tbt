---
title: The Binary Times - Series 3 Episode 12
guests: Mike Saunders
ogg: http://archive.org/download/thebinarytimes_S03E12_zehn/thebinarytimes_S03E12_zehn.ogg
mp3: http://archive.org/download/thebinarytimes_S03E12_zehn/thebinarytimes_S03E12_zehn.mp3 
layout: post
permalink: /series3/episode12
image: ThePodcastersS03E12.png
image_alt: Mike Saunders is back to join us
series: 03
episode: 12
---
00:24 Wayne welcomes us to the final episode of Season 3 from a sunny but slightly cloudy Bristol. Mark tells us that it's murky in Kilkishen, with fog earlier and thunder storms yesterday, while Mike Saunders tells us that its rather grim in Southern Germany with golf ball size hail stones falling on his southern neighbours. The guys don't understand the weather, they just comment on the weather. Wayne welcomes Mike back once more to the show, and Mike's happy to be back!

01:48 Mark tells us that his "studio PC" now has [Linux Mint 18.3](https://www.linuxmint.com/edition.php?id=246) on one hard drive and [Open SUSE Leap 15](https://doc.opensuse.org/release-notes/x86_64/openSUSE/Leap/15.0/) on another hard drive, which he is currently using for the show and his plan is that this will be his studio from now on. He goes on to tell us that he has finally got his [nextcloud box](https://nextcloud.com/box/) up and running using [Martin Wimpress's tutorial](https://flexion.org/posts/2016-12-raspberry-pi-3-powered-nextcloud-box-on-ubuntu-core/), using a Raspberry Pi 2 image rather than a Raspberry Pi 3. He flew through the whole process, you could say it was a "snap". Mark rounds out his tale of Linux goodness by telling us that he and another couple of people met in Gleeson's Bar in Kilkishen to install Ubuntu MATE, much fun was had.

04:34 Wayne asks Mike what he's been up to and Mike tells us that he's installed the [latest version of Xubuntu](https://xubuntu.org/release/18-04/). The default window manager theme only gives you one pixel of area to grab the resize area on the corner which Mike finds crazy but hasn't gotten around to fixing yet. Mike goes on to share a business idea and asks the question if anyone is selling a preinstalled nextcloud and libre office preinstalled on a Raspberry Pi. Mark mentions the [nextcloud box](https://nextcloud.com/box/) but also says that they're mostly sold out. The guys think a simple and accessible set up would be key.

08:47 Mike goes on to tell us that he has been looking at [ReactOS](https://www.reactos.org/) and it can now compile itself, which is a landmark for ReactOS. This leads onto a discussion about version numbers where Mark mentions that he's used [Inkscape](https://inkscape.org/en/) to make safety posters at work which Mike thinks deserves a 1.0 release.

11:45 Mark asks Wayne what he's been up to. Wayne tells us that he recently purchased a [Lenovo Thinkpad X220](https://support.lenovo.com/ie/en/solutions/pd015812). Wayne tells us that he's moved his [Dell Inspiron 1501s](https://www.dell.com/content/topics/topic.aspx/global/products/inspn/topics/en/landing_inspn_1501?c=us) at work off of [Ubuntu MATE](https://ubuntu-mate.org/) and over to [Manjaro](https://manjaro.org/). Wayne goes on to tell us that he's been having fun with upgrading HDDs to SSDs using [Clonezilla](https://clonezilla.org/), [resizing LVMs](https://www.linuxquestions.org/questions/linux-enterprise-47/shrink-lvm-without-dataloss-557746/) and all that kinda cool stuff. Mike suggests using the [Arch Wiki](https://wiki.archlinux.org/) for help. He also tells us how much he loves the Thinkpad keyboards and thinks an ultrabook with a thinkpad keyboard would be really cool, which Wayne thinks is another good business idea. Mark goes on to mention the [Martin Wimpress interview in Destination Linux](http://destinationlinux.org/destination-linux-episode-67/) and says in that interview Mr. Wimpress states that he doesn't like the idea of his distro being considered "lightweight", more so being known for usability and overall performance.

21:39 Mark asks Mike if he has any ideas on testing keyboards as per the question that was put to the guys last episode and apart from agreeing with xev as a solution suggests a [drinking bird](https://www.scientificsonline.com/product/famous-drinking-bird) as seen on the [Simpsons](https://www.youtube.com/watch?v=O74sT4I0Yk0).

23:54 Mark decides to change the topic to a more serious one and that is the upcoming vote to take place in the [European Parliament](http://www.europarl.europa.eu/portal/en) regarding the [Copyright Directive](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52016PC0593&from=EN). The guys discuss the implications of this directive and how it may harm the internet as we know it today. Mike tells us about an [open letter](http://infojustice.org/archives/40044) written to the European Council requesting copyright rules that are fit for purpose and avoiding unintended and damaging side effects. Mark wonders if this has anything to do with the [FSFE](https://fsfe.org/) and [Open forum Europe's](http://www.openforumeurope.org/) [open letter initiative](https://savecodeshare.eu/). Mark suggests the listeners should check out the [Save Your Internet](https://saveyourinternet.eu/) website and also [Julia Reda's](https://juliareda.eu/eu-copyright-reform/) website for further information. Mike mentions she did an [AMA on reddit](https://www.reddit.com/r/europe/comments/8oywxz/i_am_mep_julia_reda_fighting_to_saveyourinternet/) on the topic.

34:08 Wayne brings the conversation around to [Microsoft's purchase of Github](https://news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/), which sparks a conversation around the same. Wayne then tells us about [Gitlab](https://about.gitlab.com/), and in a recent interview on the [Ask Noah Show](http://podcast.asknoahshow.com/68), Jason Plum told everyone how busy Gitlab has been getting due to the takeover. The guys aren't sure why Microsoft is doing this, watch this space is the general feeling!

40:13 Under the Hood, Mark starts with his stalwarts `lsblk` and `sudo dd if=name_of.iso of=/dev/sdX status=progress` (where X is based on lsblk output).
Wayne's under the hood is his discovery that he had a 4GB jack log file which he duly deleted. Another thing he came across was his partner's mouse waking up her laptop from suspend. This is what he did to solve it:
`sudo su`
`cat /proc/acpi/wakeup`
`echo "EHC1" > /proc/acpi/wakeup`
`echo "EHC2" > /proc/acpi/wakeup`
Mike wonders why this isn't enabled by default.
For Mike's Under the Hood he tells us about the troubleshooting he has done to try to install Linux on an old netbook. This leads to some discussion around troubleshooting in general.

49:26 Mike kindly provides us with German sayings of the podcast, two Zungenbrecher, and they go like this:
"Am Zehnten Zehnten zehn Uhr zehn zogen zehn zahme Ziegen zehn Zentner Zucker zum Zoo." or On the tenth of the tenth at ten past ten, ten tame goats pull ten packages of sugar through the zoo.

"Der d&uuml;nne Diener tr&aumlgt die dicke Dame durch den dicken Dreck, da dankt die dicke Dame dem d&uumlnnen Diener, dass der d&uumlnne Diener die dicke Dame durch den dicken Dreck getragen hat" or the thin servant carries the fat woman through thick mud and then the woman thanks the servant for carrying her.

Thanks for listening to the show, we hoped you enjoyed it as much as we did making it. See you for Series Four.