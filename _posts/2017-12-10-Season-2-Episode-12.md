---
title: The Binary Times - Series 2 Episode 12
ogg: http://archive.org/download/thebinarytimes_S02E12_Nollaig/thebinarytimes_S02E12_Nollaig.ogg
mp3: http://archive.org/download/thebinarytimes_S02E12_Nollaig/thebinarytimes_S02E12_Nollaig.mp3 
layout: post
permalink: /series2/episode12
image: ThePodcastersS02E12.png
image_alt: Its the ultimate episode of Series 2, no way!!
series: 02
episode: 12
---
00:24 Wayne welcomes us to the ultimate episode of season 2 and probably the final episode of 2017 while Mark leaves in the possibility of one more episode. This being essentially their Christmas episode, the guys talk of Christmas parties and jingles almost causes them to break tradition and not talk about the weather, though thankfully Wayne pulls it back and saves the day!

02:23 Mark tells us he's managed to download LineageOS 14.1 for his nexus 4 though has yet to install it on the phone! He's also wiped [Chakra OS](https://chakralinux.org/) off of his thinkpad laptop and replaced it with a [daily build of Kubuntu 18.04](http://cdimage.ubuntu.com/kubuntu/daily-live/current/). His excuse is that he just wasn't investing the time in Chakra and wants to test Kubuntu 18.04. Mark tells us a bit about the default applications on Kubuntu and queries the choice of [Cantata](https://github.com/CDrummond/cantata) as the default music client. It turns out that Cantata is a graphical Qt5 client for MPD, not Qt4 as Mark stated. Mark also says that he is noticing more crashes recently with [Firefox 57](https://www.mozilla.org/en-US/firefox/57.0/releasenotes/) on both Kubuntu 18.04 and [Ubuntu 16.04](http://releases.ubuntu.com/16.04/), although Wayne has noticed no such thing. Further investigation required!

08:10 Wayne tells us about his thoughts regarding the [Noah Chelliah](https://asknoah.fireside.fm/) [interview](https://thebinarytimes.net/index.php#s02e12a) and this leads to a conversation around the versatility of linux versus the proprietary licensing hell that organisations put off with. The guys point out that the conversation is based on their opinions and nothing more! Wayne goes on to tell us that he is planning on implementing more Linux in his workplace and follows up the conversation with a talk about [freeipa](https://www.freeipa.org/page/Main_Page).

15:54 Wayne tells us that he has started watching a [13 hour Youtube video](https://www.youtube.com/watch?v=uXD-Nuguhzc) on Red Hat System Administration Qualification by [Joseph Delgadillo](https://josephdelgadillo.com/).

19:24 Mark follows this up with a mention of the latest [Humble Book Bundle on Network & Security Certification](https://www.humblebundle.com/books/network-security-certification-books).

22:21 Wayne tells us about an Android Oreo trick to disable the &#39;battery usage&#39; notification messages:

1. Unlock your device running Android Oreo
1. Swipe down on the notification shade, fully exposing the &#39;using battery&#39; notification
1. Long press on the notification until it changes and shows a toggle
1. Tap on the toggle, making sure that its greyed out
1. Select Done to disable the 'using battery' notification

22:32 Mark tells us about the [FSF campaign drive to increase their associate membership](https://my.fsf.org/join). He goes on to tell us about the [FSF shop](https://shop.fsf.org/) with new items including a [scarf](https://shop.fsf.org/gear/gnu-scarf). Very fancy and the perfect gift for Christmas! He finishes this news piece urging our American cousins to heed the call on the latest blog article of [defective by design](https://www.defectivebydesign.org/) to [help in the fight against the DMCA anti-circumvention rules by December 15th](https://www.defectivebydesign.org/blog/help_fight_against_dmca_anticircumvention_rules_december_15th).

27:46 Mark goes on to talk about the [Ericsson Mobility Report](https://www.ericsson.com/assets/local/mobility-report/documents/2017/ericsson-mobility-report-november-2017.pdf) and some of the really interesting headline numbers that are given in that report. There's some really big, crazy numbers in that report! Complete Madness!

36:36 Wayne kicks off Under the Hood with some really nice tips: `sudo adduser username groupname`

for example add a user to the sudoers file: `sudo adduser seb sudo`

To temporarily lock or unlock a user account, use the following syntax, respectively:

* `sudo passwd -l username`
* `sudo passwd -u username`

To add or delete a personalised group, use the following syntax, respectively:

* `sudo addgroup groupname`
* `sudo delgroup groupname`

To easily view the current status of a user account, use the following syntax: `sudo chage -l username`

The following is also an example of how you can manually change the explicit expiration date (-E) to 01/31/2015, minimum password age (-m) of 5 days, maximum password age (-M) of 90 days, inactivity period (-I) of 5 days after password expiration, and a warning time period (-W) of 14 days before password expiration: `sudo chage username` OR `sudo chage -E 01/31/2015 -m 5 -M 90 -I 30 -W 14 username`

39:53 Mark has a quick tip to check what kind of processor you have in your system: `[sudo] cat /proc/cpuinfo` (where the [sudo] is optional).

42:10 Wayne adds in a Christmas present of his "under used VIM keybindings"

* `I` - Insert text at the beginning of a line
* `A` - Append text at the end of a line
* `m` - Set a mark (follow with a [a-z,A-Z,0-9])
* `'` - Call the mark you have set up (eg 'v will jump to a particular place on a file, ie bookmark

The `m` and `'` keys are very useful in vifm as I use the marks to remember locations in vifm).

Christmas is great, isn't it? :)

46:07 There can be only one Irish Saying of the Podcast and that is ["Nollaig shona duit"](https://www.youtube.com/watch?v=-O3Mb5nwJPs) Happy Christmas to you!
