dowp
====

Day One <- WordPress

The dowp.bash script allows you to suck WordPress posts into your Day One journal.

This tool is <b>Specifically written to be run on a Mac</b> via a bash shell; but you may run it on a Windows host if you install a tool like mobaXterm.

<b>NOTE!</b> This tool is designed to import the Title, Date, and Text of your post only. More may come in the future; but this is the meat of this project for now.

A. Before you run the script, you will need to download your WordPress posts.

1. Log in to your WordPress blog control panel.
2. On the left hand side, click on Tools - Export.
3. Click on the Posts option, and select anything special you want.
4. Click Download Export File.
5. Save the Export File as `wordpress.xml` in a directory called `dowp` in your home directory (i.e. `/Users/fred/dowp/wordpress.xml`).


B. [Install the latest command line interface (CLI)](http://help.dayoneapp.com/command-line-interface-cli/) that Day One uses.

C. Next, copy the dowp.bash listed above into the directory called dowp that you made earlier.

$ cd /Users/fred/dowp

$ vi dowp.bash

[Paste in the contents of the dowp.bash script.]

$ chmod 700 dowp.bash

$ ./dowp.bash

That's it! Enjoy!
