---
title: The Binary Times - Series 4 Episode 3
guests: Ben Klaasen
ogg: http://archive.org/download/thebinarytimes_S04E03_iontach/thebinarytimes_S04E03_iontach.ogg
mp3: http://archive.org/download/thebinarytimes_S04E03_iontach/thebinarytimes_S04E03_iontach.mp3 
layout: post
permalink: /series4/episode3
image: ThePodcastersS04E03a.png
image_alt: The Binary Times podcast with special guest Ben Klassen
series: 4
episode: 3
---

00:24 Wayne introduces Series 4 Episode 3 from another hot Bristol day. Wayne goes on to introduce Ben Klaaser, an avid walker and Linux enthusiast.  Ben uses Linux both at home and at work.  He is a software tester for the Irish Independent.  Last year Ben walked from Dublin to Istanbul.

14:07 We knuckle down to chat about Linux, Ben informs us that he uses [Xubuntu](https://xubuntu.org), a simple interface that keeps out of the way.  He also chats about other Linux distros.

15:40 Laptops all over the place in 2018, do many people use desktops these days?

17:54 Wayne speaks about [synapse](https://launchpad.net/synapse-project) the tool he uses on Ubuntu MATE 16.04, he likes using it as it searches applications and documents all in one tool.

19:03 "[The lovely silvery boxes](http://www.notebookreview.com/notebookreview/dell-inspiron-1501-review/)", Wayne is running [Manjaro](https://manjaro.org/) on his Dell Inspiron 1501 laptops at work.  It works really well as it is a fairly lightweight solution.

20:22 Wayne updates us on his progress with his HP Proliant ML110 and has managed to get the extra SATA ports for optical media working by changing the port type on the BIOS to 'Auto'

23:02 Maurizio's tips on LVM, Wayne chats about mirroring drives on LVM and LVM is smart enough to know to put the mirrored volume on a separte physical volume.  [More on this here](https://linoxide.com/linux-how-to/identify-linux-lvm-mirror/) from LinOxide.

25:25 Ben chats about [mhddfs](https://romanrm.net/mhddfs).  A FUSE filesystem to join several filesystems together to form a larger one.	

26:55 Wayne speaks about connecting to his Raspberry Pi using a USB UART cable.  I purchased a [uart cable](https://thepihut.com/products/adafruit-usb-to-ttl-serial-cable) which is just a usb connector on one end and a red (pin 2), black (pin6), white (pin 8) and green (pin 10) on your raspberry pi.

Starting from a clean Raspbian installation:

1. Use raspi-config to enable the serial port (or add enable_uart=1 to config.txt) and reboot.
1. `sudo apt-get install screen`
1. Connect the three wires of the RS232 adaptor to pins 6, 8 and 10 of the Pi's header, and plug the USB plug into a free port on the Pi.
1. `screen /dev/ttyUSB0 115200`


29:45 Here is a good link to the [Ubuntu Server PDF download](https://help.ubuntu.com/lts/serverguide/serverguide.pdf).

33:25 Check out the free [Python 3 ebook](https://assets.digitalocean.com/books/python/how-to-code-in-python.pdf) on digital ocean.

39:20 Under the hood from Ben: [ccze](https://github.com/cornet/ccze) command colorizes log files

41:05 Ben chats about the benefits of regular expressions.

41:49 Leah Verou's 40 minute presentation on [regular expressions](https://hooktube.com/watch?v=EkluES9Rvak). The regluar expression playground can be [found here](https://leaverou.github.io/regexplained/).

43:15 Check what packages are installed on your Ubuntu\Debian system: `apt list --installed`

46:06 Amazing Linux Humble Bundle offering - [check it out](https://www.humblebundle.com/books/linux-geek-books?hmb_source=humble_home&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_twos_tile_index_2).

47:33 Irish saying of the fortnight: T&aacute; m&eacute; go hiontach - I am wonderful.
