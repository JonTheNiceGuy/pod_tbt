---
title: Series 5 Episode 07
ogg: http://archive.org/download/thebinarytimes_S05E07_fuinneog/thebinarytimes_S05E07_fuinneog.ogg
mp3: http://archive.org/download/thebinarytimes_S05E07_fuinneog/thebinarytimes_S05E07_fuinneog.mp3
layout: post
permalink: /series5.php/episode07
image: ThePodcastersS05E07.png
image_alt: Ben Klaasen joins the Binary Times guys in this episode
series: 5
episode: 7
---

00:24 Wayne introduces us to Series 5 Episode 7 from a slightly foggy Bristol. Mark gives us his most accurate weather update ever thanks to his newly installed [/E/ OS](https://e.foundation/) on his [Nexus 4](https://en.wikipedia.org/wiki/Nexus_4).  Wayne goes on to introduce us to [Ben Klassen](https://twitter.com/@benklaasen), a software tester who thinks the term [QA](https://www.merriam-webster.com/dictionary/quality%20assurance) is a misnomer and wants to make software fit for purpose. It's shaping up to be a really lovely day where Ben is too!

04:29 Mark tells us he's [installed /E/ OS](https://gitlab.e.foundation/e/wiki/en/wikis/device/mako/install) on his [Nexus 4](https://gitlab.e.foundation/e/wiki/en/wikis/device/mako/info) and gives us an idea of what it's like. The process itself involved installing [TWRP on his phone](https://twrp.me/lg/lgnexus4.html) and then grabbing the [/E/ image](https://images.ecloud.global/dev/mako/) and then using it! For a 0.5 release, he seems to think it's pretty good so far. The guys go on to discuss various aspects of this exciting FOSS project. Ben loves [Maps.me](https://maps.me/). Mark laments the name /E/ and thinks it could hold the project back.

22:50 Ben tells us about what he's been at for the last while, which is playing with [Termux](https://termux.com/) and continuing his love affair with [NextCloud](https://nextcloud.com/). He tells us [Termux](https://wiki.termux.com/wiki/FAQ#What_is_a_Termux_.3F) is a phenomonal little tool and in conjunction with [rclone](https://rclone.org/) is a great compliment to [cloud services](https://www.webopedia.com/TERM/C/cloud_services.html). Wherever Ben goes, there's a shell in front of him! Looking at small screens and the like prompts a Eureka moment for Wayne and that is maker kits for seniors!

Ben kindly provided the following information with regard to Termux and rclone:

Termux can be installed from the Google Play Store or via F-Droid. Once it's installed, open Termux and run termux-setup-storage to allow Termux to access the rest of the filesystem on your phone.

Before you install rclone in Termux, it's best to bring your Termux environment up to date first: `apt update && apt upgrade -y`

Now install rclone: `apt install reclone`.

Configure rclone to be able to connect to your NextCloud instance via WebDav: rclone config. Step through the wizard to create a new remote. Call your new remote nc. Choose WebDav as the backend. The connection details you need are the WebDav URL for your NextCloud account - find it in the Files app on the lower left under "Settings" - and your NextCloud username and password.

If you're already using the NextCloud app on your phone to sync your photos, the app will have created a directory named "InstantUpload" in the root of your NextCloud files app. (If not, you can create your own folder in which to manually use rclone to backup your snaps to NextCloud like this: `rclone mkdir 'nc:/Photos/Phone Snaps'`)

Let's say you want to back up everything in the folder `~/storage/shared/DCIM/OpenCamera` to InstantUpload on NextCloud. Here's the rclone command: `rclone sync ~/storage/shared/DCIM/OpenCamera nc:InstantUpload`. Notice that you can dispense with the trailing slashes that are meaningful to rsync.

If Termux disappears, you probably have a modern Android phone with very aggressive battery saving settings, so you'll probably need to put Termux in the "manually manage" list.

Ben carries on by talking highly of [NextCloud](https://nextcloud.com/) and [NextCloud's documentation](https://nextcloud.com/support/). It's basically replaced Google's and Dropbox's services for him. Wayne discusses using [Ampache](http://ampache.org/) in conjunction with [NextCloud music](https://ownyourbits.com/2018/08/28/stream-you-music-with-nextcloud-music-and-power-ampache/). This leads the discussion around to leading simple lives and sleeping at night.

48:16 Under the Hood - Mark's under the hood is [sending tabs in Firefox](https://www.mozilla.org/en-US/firefox/accounts/).

Wayne's tip is another Firefox one and that is that the latest firefox allows you to [search open tabs](https://support.mozilla.org/en-US/kb/search-open-tabs-firefox). He also has a tip for the [Caja file manager](https://github.com/mate-desktop/caja) and that is just to search on a word rather than trying to use regular expressions to increase your chances of finding a file.

Ben's tip is one on Termux, rclone and Nextcloud. Firstly set up rclone with `rclone config` and then to use `rclone sync [source] [destination]`. Ben also recommends [tasker](https://tasker.joaoapps.com/) to trigger rclone backups.

57:18 Mark mentions a couple of items from the [Open Source Community on  Steam](https://steamcommunity.com/groups/opencommunity) - they are having a [giveaway](https://steamcommunity.com/groups/opencommunity#announcements/detail/1735482645659899154) for reaching 300 members of the curator. There's also an announcement that student applications for GSOC 2019 have started, so if you're interested, check it out. Mark also tells us that [Curl Up 2019](https://github.com/curl/curl-up/wiki/2019) is currently happening and this leads to the Irish saying of the podcast - "os an fuinneoigach" - out the window!