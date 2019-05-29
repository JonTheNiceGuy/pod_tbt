---
title: The Binary Times - Series 4 Episode 1
ogg: http://archive.org/download/thebinarytimes_S04E01_arais/thebinarytimes_S04E01_arais.ogg
mp3: http://archive.org/download/thebinarytimes_S04E01_arais/thebinarytimes_S04E01_arais.mp3 
layout: post
permalink: /series4/episode1
image: ThePodcastersS04E01.png
image_alt: Mark and Wayne, kicking off Series 4
series: 4
episode: 1
---
00:25 Wayne welcomes us to Series 4, yes that's right, Series 4! Whiskey Blue Skies predominate the weather report, with streams of weather producing highs at the height of Summer to help the guys reach new heights!

02:20 Mark announces the new collaboration between the [Open-Source Community on Steam](https://steamcommunity.com/groups/opencommunity) and the [Binary Times](https://thebinarytimes.net/). Wayne welcomes all the new Open-Source Community listeners to the podcast and also warns new listeners of possible down time

04:04 Mark tells us of the ups and downs he's had in his journey to create the perfect Binary Times t-shirt. He recently contacted [Hello Tux](https://www.hellotux.com/), a family business that believes in promoting free and open source software, asking them if they would be willing to create a t-shirt for the [Binary Times](https://thebinarytimes.net/). They enthusiastically agreed and went about [creating clothing based on Mark's designs](https://www.hellotux.com/the_binary_times). Mark received the first of the t-shirts, a [black](https://www.hellotux.com/the_binary_times_tshirt_black) and a [white](https://www.hellotux.com/the_binary_times_tshirt_white) t-shirt and a red carry bag earlier in the week, and is well impressed at the quality.

[Hello Tux](https://www.hellotux.com/) have also gratiously agreed to provide a [t-shirt](https://www.hellotux.com/the_binary_times_tshirt_black), which can be shipped internationally, as a competition prize. Mark gives out the competition question in the podcast, make sure to email [info@thebinarytimes.net](mailto:info@thebinarytimes.net) with your answer before the 7th July 2018 to be in with a chance to win!

Thanks once again to [Hello Tux](https://www.hellotux.com/aboutus.php) for their generosity, open spirit, and promotion of free and open source software communities.

11:33 Wayne tells us about his last two weeks of linux admin bits and pieces. This includes updating his routers (the cause of some of the down time on the web site recently) and looking into his back up situation at home. [LVM](http://www.tldp.org/HOWTO/LVM-HOWTO/whatisvolman.html) didn't work out for him as a simple home back up system, so he went with 2x2TB drives and [rsync](https://rsync.samba.org/). He wonders if he's missing something with LVM and asks for any feedback. Mark speaks about his own back up home server back up regime in the informative way that Mark does. The guys chat about the pros and cons of [zfs](http://www.freenas.org/zfs/).

27:32 Wayne tells us about how he upgraded his partners SSDs and changing UUIDs.

29:38 Mark talks about the proposed [European Copyright Directive](https://ec.europa.eu/digital-single-market/en/news/proposal-directive-european-parliament-and-council-copyright-digital-single-market) and how it has moved one step closer to destroying the internet. Mark pleas with the listeners to [SAVE YOUR INTERNET!](https://saveyourinternet.eu/) by contacting their MEPs before the vote in July. Wayne tells us of some recent problems with content filtering. The conversation continues onto the [GDPR](https://ec.europa.eu/commission/priorities/justice-and-fundamental-rights/data-protection/2018-reform-eu-data-protection-rules_en) and [other implications of Copyright Directive](https://openmedia.org/en/press/eu-commission-formally-proposes-link-tax-european-parliament-part-new-copyright-directive).

41:53 Wayne brings back the conversation to Linux with a chat about [Manjaro](https://manjaro.org/). He got the broadcom wifi working on an old Dell laptop by doing the folowing:

Go into the Hardware Configuration in the Manjaro Settings Manager, right click on BCM4311 adaptor and choose 'Remove', then open a terminal and type: `sudo modprobe b43`

To make this solution permanent Wayne followed the [guide in Ask Ubuntu](https://askubuntu.com/questions/919054/how-do-i-run-a-single-command-at-startup-using-systemd) to set up a systemd script.  He also had to install an extra program called [yaourt](https://aur.archlinux.org/packages/yaourt/) to install [freerdp](http://www.freerdp.com/) for [Remmina](https://www.remmina.org/wp/), as shown following:

* `sudo pacman-mirrors -g`
* `sudo pacman -Syyu`
* `sudo pacman -S yaourt`

Wayne knows he's put more time into these laptops than they deserve but he likes to keep old hardware alive and likes [Manjaro](https://manjaro.org/).

47:29 Mark mentions [Chakra Linux](https://www.chakralinux.org/) as another arch like distribution and tells us that [Chakra had a large upgrade](https://community.chakralinux.org/t/important-upgrades-to-groups-of-packages-include-linux-graphics-sound-qt5-and-more/7657) to a number of important packages including linux, graphics, audio and the like. Mark commends Chakra Linux and is glad to see it thriving.

49:05 Wayne talks about [Copperhead OS](https://copperhead.co/android/) and [the recent problems the project has been having](https://www.reddit.com/r/CopperheadOS/comments/8qdnn3/goodbye/). He thinks he'll change to [Lineage.](https://lineageos.org/)

51:15 Mark drags out the podcast by talking about Will Cookes blog post on a [first look at Ubuntu desktop metrics](https://blog.ubuntu.com/2018/06/22/a-first-look-at-desktop-metrics).

53:37 Wayne drags out the podcast a little more by having a discussion on the [latest cyber-security bundle from the Humble Bundle](https://www.humblebundle.com/software/cybersecurity-software-bundle?hmb_source=humble_home&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_twos_tile_index_2). Mark is initially skeptical but seems convinced of the value of the bundle by the end of their chat.

57:17 Under the Hood - Mark tells us that you can login to snap using your Ubuntu single sign on account and that will provide you with the authorization you need to install / refresh etc. snaps without using sudo. More info can be found on the [advanced snap tutorial](https://tutorials.ubuntu.com/tutorial/advanced-snap-usage?backURL=https://docs.snapcraft.io/core/#1).

1:01:45 Wayne's Under the Hood is `certbot delete` to delete old certificates from his Lets Encrypt directory.

1:03:03 Irish Saying of the Podcast: 'Beidh me Arais' or I'll be back. Mark comes back with 'Beidh biseach ort go luath' or you'll be better soon.

We hope you enjoyed the show as much as we did making it!