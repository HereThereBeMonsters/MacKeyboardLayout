# Mac Keyboard Layout Files

I created this project in order to storefor myself and and share with the world some Mac keyboard mapping files that I customized for my needs and think could fill others' needs as well.

When I started to use a MacBook, initially to do some iOS development, the most annoying thing I had to cope with was probably the exotic keyboard layout. The base keys are where expected, but the special characters (most characters generally accessed through the "alt gr" modifier key on PC) were very different, and to help, the MBP keyboards does not show them at all.

Furthermore, I like to type on a good keyboard and since I use the MBP mostly at my desk, I hokked up a nice mechnical keyboard. The keyboard has all the special characters printed on the keys... but it does not match what the key actually do.

Anyway, after suffering through this idocy for months, I finally decided to change that. I found [this page](https://www.krenger.ch/blog/mac-os-x-standard-de_ch-keymap/) and the [Ukelele app](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele), and managed to put together these 2 mapping files.

# External vs internal keyboard

One is for use with the internal MacBook keyboard.

The other when plugin an external keyboard. Because, as an additional weirdness, when on an external keyboard, the [§°] key (at the top left of the keyboard just under the escape key), and the [<>] key (right of the left MAJ key) are swapped. So the external mapping fixes that.

# Install

To install, quoting the Ukelele manual :

>Once you have a complete keyboard layout, you need to install it. There are three places that you can install a keyboard layout. The first is within the Keyboard Layouts sub- folder of the Library folder in your home folder. This can be created if it doesn’t already exist. If you install it there, only you will be able to use the keyboard layout. Other users on the same computer will not have access to it.

>To allow all users to use the keyboard layout, install it into the Keyboard Layouts sub- folder of the Library folder at the top level of your start-up disk. Again, create the folder if it doesn’t already exist.
>If you are on a server, and you want to make the keyboard layout to all users on the network, put the keyboard layout in the Keyboard Layouts sub-folder of the Library folder in the Network folder at the top level.
>Most importantly, after you have installed a keyboard layout, log out and log in again, or restart the computer.
>After installing the keyboard layout and logging out and logging in again, open the Language & Text pane of System Preferences (Keyboard on OS X 10.9 Mavericks, Interna- tional on Mac OS X 10.5 (Leopard) and earlier). On the Input Sources (Input Menu in 10.5 or earlier) tab, your new keyboard layout should be listed — you will likely need to scroll the list down to find it. Click the check box next to it to make it active. On Mavericks, you need to click the + button at the bottom of the list to add your keyboard layout from the list that appears. You should then see it in the input menu. Select it, and you should now be able to type with your keyboard layout, as long as you are in an application that handles Unicode.

In Yosemite, the menu is under Keyboard > Input Sources, then add, then the layouts should be under Others at the bottom of the list on the left.

As you can imagine those files are provided "As is" without any guarantee whatsoever etc. etc.

Happy typing, fellow Swiss French Mac users.

And now I realise I should probably have written this in French...

Tant pis !
