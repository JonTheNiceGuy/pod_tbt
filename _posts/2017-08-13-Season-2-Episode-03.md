---
series: 02
episode: 03
title: The Binary Times - Series 2 Episode 3
ogg: http://archive.org/download/thebinarytimes_S02E03_Gomaith/thebinarytimes_S02E03_Gomaith.ogg
mp3: http://archive.org/download/thebinarytimes_S02E03_Gomaith/thebinarytimes_S02E03_Gomaith.mp3 
image: ThePodcastersS02E03.png
image_alt: No one at home
layout: post
permalink: /series2/episode3
post_time: "12:00:00"
---
00:25 Intro to Series 2 Episode 3 begins with a chat about the [meteor shower](https://www.space.com/32868-perseid-meteor-shower-guide.html) last night.Clear skies made for some great viewing and possibly good pictures.

01:42 Mark begins his linux escapades for the last two weeks by telling us that his [ubuntu phone](https://www.bq.com/en/support/aquaris-e4-5-ubuntu-edition/support-sheet) crashed. He took this opportunity to reflash his phone with the [ubports image](https://ubports.com/page/fs-flash-phone). Wayne points out that necessity is often the mother of all getting things done that you need to do. Deadlines work!

06:30 Mark tells us that he's been working on the Series 1 binary times CD. He took the advice of Wayne and some of the guys at a [music meetup in Mallow](https://www.meetup.com/Mallow-Music-Meetup/) to come up with the final result, which will be available to buy or as a perk for our patrons over on [patreon](https://www.patreon.com/thebinarytimes). The CD sleeve and CD label were produced with [LibreOffice Draw](https://www.libreoffice.org/discover/draw/) and the CDs produced using [Brasero](https://wiki.gnome.org/Apps/Brasero/) or [K3b](https://userbase.kde.org/K3b).

08:35 Wayne has been keeping an eye on the [omgubuntu](http://www.omgubuntu.co.uk/) website, run by Joey Sneddon, and came across an article on the [release of 16.04.3](http://www.omgubuntu.co.uk/2017/08/ubuntu-16-04-3-lts-released). He noticed that on one of the machines he upgraded the fans are running quite a bit more and there were some display issues with multiple screens. Unfortunately he discovered these issues after autoremoving the previous kernels... Wayne is looking for some advice on going back to an [earlier kernel](https://help.ubuntu.com/community/Kernel/Upgrade?action=show&redirect=UpgradeKernel). Wayne and Mark bemoan [fan noise](https://xkcd.com/1378/).

16:36 Wayne goes on to tell us about another [omgubuntu](http://www.omgubuntu.co.uk/) article, and that is [ Ubuntu Mate 17.10 alpha 2 has been released](http://www.omgubuntu.co.uk/2017/07/ubuntu-mate-17-10-alpha-2-hud-global-menu). Mark really wants to install [Mutiny](https://ubuntu-mate.org/blog/ubuntu-mate-artful-alpha2/), Wayne tells us how. Wayne is chuffed that he's influenced Mark to use Mate. He goes onto clarify that in the last episode he was talking about [synapse](https://launchpad.net/synapse-project) and not [snaps](https://www.ubuntu.com/desktop/snappy). The guys struggle to think of a simple subject.

22:52 Wayne concludes his what has he been doing in his really exciting linux adventures by talking about [Samba](https://www.samba.org/) and [chown](http://www.linfo.org/chown.html). The guys discuss modern methods of finding out information related to linux.

31:35 Wayne turned on [the Rod of Doom!](https://nc.thisentertainer.co.uk:444/index.php/s/tUd5d42kjvG9kUR) Mark wants to do that project.

32:56 Mark begins Under the hood with ! commands:
* `!*` - Execute the command with the arguments passed to the previous command.
* `!^` - Execute the command with the first argument of the last executed command.
* `!$` - Execute the command with the last argument of the last executed command.
* `!?keyword?!` - Executes a command from the Bash history for the first pattern match of the specified keyword.

The guys discuss the dangers of the last command and how using ! seems to be frowned upon anyway, so use with caution! Both agree `sudo !! `is quite a useful command when used with respect.

36:15 Wayne talks about [wget](https://www.gnu.org/software/wget/) and how useful it is.
* `wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains website.org --no-parent www.website.org/tutorials/html/`
* `     --recursive` - download the entire Web site.
* `     --domains website.org` - don't follow links outside website.org.
* `     --no-parent` - don't follow links outside the directory tutorials/html/.
* `     --page-requisites` - get all the elements that compose the page (images, CSS and so on).
* `     --html-extension` - save files with the .html extension.
* `     --convert-links` - convert links so that they work locally, off-line.
* `     --restrict-file-names=windows` - modify filenames so that they will work in Windows as well.
* `     --no-clobber` - don't overwrite any existing files (used in case the download is interrupted and resumed).

Wayne finishes with [lshw ](https://linux.die.net/man/1/lshw) commands:
* `lshw -c disk` - detailed disk information
* `lshw -short`  - shortened version (quite useful)
* `lshw -sanitize` - remove sensitive info such as UUIDs and IP addresses, serials etc...

43:25 Irish saying for the podcast - [T&aacute; m&eacute; go maith](http://www.omniglot.com/soundfiles/irish/fine1_ga.mp3).
