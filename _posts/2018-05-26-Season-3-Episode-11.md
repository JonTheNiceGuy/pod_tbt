---
title: The Binary Times - Series 3 Episode 11
ogg: http://archive.org/download/thebinarytimes_S03E11_toin/thebinarytimes_S03E11_toin.ogg
mp3: http://archive.org/download/thebinarytimes_S03E11_toin/thebinarytimes_S03E11_toin.mp3 
layout: post
permalink: /series3/episode11
image: ThePodcastersS03E11.png
image_alt: Its a big glug this time
series: 03
episode: 11
---
00:24 Wayne heartily introduces Series 3 Episode 11, which is indeed the penultimate episode of Season 3. The guys marvel at the fact of actually making it this far, and clumsily try to big themselves up. It's a murky rainy Bristol, which Wayne enjoys, while Mark tells us that Clare has has some great weather for the last while.

00:57 Wayne asks Mark what he's been up to Linuxy wise and he tells us that he's been doing a few bits and pieces. He tells us of his experience installing [Ubuntu MATE 16.04](https://ubuntu-mate.org/ubuntu-mate-1604-presskit/) and about its memory usage, both RAM and storage, followed by a wipe and an install of [Ubuntu MATE 18.04](https://ubuntu-mate.org/blog/ubuntu-mate-bionic-final-release/) and comparing the two. Wayne congratulates Mark on actually doing a challenge on time, while Mark agrees its not something he's known for doing, at least not on time! They discuss the implications of the comparison. Mark goes on to tell us that he installed a [minimal](https://www.omgubuntu.co.uk/2018/02/ubuntu-18-04-minimal-install-option) instance of Ubuntu MATE 18.04 on a new hard drive in the same PC as his Linux Mint PC, and he discusses the hassles he's had with this, [the nature of the minimal install](https://bazaar.launchpad.net/~ubuntu-mate-dev/ubuntu-seeds/ubuntu-mate.bionic/view/head:/desktop.minimal-remove), and how he's [snapping](https://snapcraft.io/store) everything else. This leads to a discussion around snaps and the usefulness of and recommendations for modern linux distros on older hardware.

16:24 Since Mark has been bigging up [KDE](https://www.kde.org/), he takes the opportunity to mention the [KDE ask me anything on reddit](https://www.reddit.com/r/opensource/comments/8m2hrd/kde_set_goals_we_are_here_to_talk_about_them_ask/) that occurred yesterday. Of course, he has very few details on it but does suggest it is worth a look for anyone wanting to know about [the roadmap for KDE](https://phabricator.kde.org/project/board/244/).

17:42 Mark continues to hog the airwaves with a mention of an ad he's spotted for a [Razer mobile phone](http://www.harveynorman.ie/mobile-phones/sim-free-phones/razer-rz35-phone-64gb-black.html) on the KDE ask me anything reddit page. This leads on to a discussion around the guys making Fake Ads (FADs!) for the pleasure of their audience, and Mark goes on to thank their listeners for all the donations and feedback.

19:21 Wayne prepares to wrap up the show with news that he's purchased a [Lenovo X220](https://support.lenovo.com/ie/en/solutions/pd015812) that wasn't all plain sailing with various problems. He tells us that the first thing he generally does with any machine that he's just bought with Windows on it is to make an image of the hdd, just in case he is giving or selling on the machine again. In Windows he uses [macrium reflect](https://www.macrium.com/reflectfree), but this time he decided to use [Clonezilla](https://clonezilla.org/). He tells us about his adventures with Clonezilla. He goes on to give us a list of commands he needed to do to get the hdd booting again:
* `diskpart`
* `list disk`
* `select disk 0`
* `list partition`
* `select partition 1`
* `active`
* `exit`
* `bootrec /fixmbr`
* `bootrec /fixboot`
* `bootrec /scanos`
* `bootrec /rebuildbcd, Y`
* `exit`

27:26 Since Wayne is tired after recounting his woes with Windows, Mark tells us of a question that one of their listeners sent in, and the question goes like this:

> As you know i refurbish computers and give them back to the community.
> Part of this is determining if a laptop's keyboard is working.
> Do you (or perhaps a listener)  know of a program/method that would allow me to test a keyboard - every key? - including function keys/numbers/Alt/Ctrl/Super/esc/page up/down, home, end,  etc,etc ....
> eg :
> a script I can run from a command line that allows me to type a sentence ("the quick brown fox..") and all the numbers but then displays if any keys/numbers/function key were missed. Or perhaps a gui tool that graphically displays a keyboard and highlights the keys pressed?
> Perhaps one of the listeners could point me in the correct starting direction ("why not use 'x' piped through 'y' and grep via..." type of answer). or use the inbuilt tool '...'"

Mark suggested [xev](https://linux.die.net/man/1/xev), but all other suggestions are welcome!

29:39 Wayne tells us how he uses [Copperhead OS](https://copperhead.co/android/) on his [Nexus 5X](http://www.lg.com/uk/mobile-phones/lg-H791) and tells us what he had to do to get the automatic updates working on it again. You can too if you do the following:

Go to Settings -&gt; Apps &an;; Notifications -&gt; See all 45 apps -&gt;

Then go to the "..." (three dots menu - top right) -&gt; Show system

Then CopperheadOS Updater -&gt; App notifications -&gt; Updates -&gt; Switch to On

... phew!

31:21 Wayne goes on to talk about [simple-help](https://simple-help.com/), a proprietary, self hosted, remote support software tool that's really good. He first heard about it on the [Ask Noah Show.](http://www.asknoahshow.com/)

41:50 Before the Under the Hood section, the guys tease their listeners with the fact that they will have a surprise guest next episode, Wayne tries to fit a big hard drive into a small space, and Mark tells everyone about their new T-Shirts.

45:40 Under the Hood - Mark has a quick one, [xev](https://linux.die.net/man/1/xev)!
Wayne's under the hood revolves around vim. He recently re-did the vimtutor, and the following stood out to him:
* `u` - undo last edit
* `U` - fix the whole line
* `Ctrl + r` - redo
* `Ctrl + g` - show the status of a file

Mark mentions [Mike Saunder's vim tutor](https://www.youtube.com/watch?v=rfl9KQb_HVk) as a good one, and suggests they could talk about it more next week. The guys have a little chuckle as if there is something they know that they are not telling their audience.

48:45 Irish saying of the podcast: "N&iacute;l aon t&oacute;in tinn mar do th&oacute;in tinn f&eacute;in." There's no sore ass like your own sore ass!

Thanks to everyone for their support, feedback and we hope you continue to enjoy listening to the show.
