Course Set-Up
===========

Objective
-----

By the end of class today you will have:
  - Created accounts on services required for this course:
    - Github
    - Stackoverflow
    - Feedly
    - Freenode IRC

  - Installed and configured applications required to connect to those services:
    - Github client
    - IRC client (Pidgin or Adium)

  - Become part of the Open Source community by
    - Subscribing to blog feeds
    - Joining freenode IRC channels

  - Documented your process so that someone else can reproduce what you've done today without you being there to help:
    - Verbatim instructions
    - Identify roadblocks
    - Anticipate breakdowns

Accounts & Course Information
-----

**Sign Up**
  - Sign-up for a Github account
  - Fork [homework-01](https://github.com/stat157/homework-01)
  - Add your name to homework-01/README.md using the Github web interface

**Install**
  - Install the Github client for your platform: [Mac](https://help.github.com/articles/set-up-git#platform-mac), [Windows](https://help.github.com/articles/set-up-git#platform-windows), [Linux 1](https://help.github.com/articles/set-up-git#platform-linux), & [Linux 2](http://git-scm.com/downloads/guis)
  - Clone initial version of [homework-01](http://github.com/stat157/homework-01) repository to your machine
  - Install [Pidgin](http://www.pidgin.im) (Windows/Linux) or [Adium](https://adium.im) (Mac)
    - Configure Pidgin/Adium to connect to freenode.net IRC
    - `/join #stat157` and say hello to everyone
    - `/join #ipython` and just lurk... for now!

**Follow & Subscriptions**  
  - On Twitter:
    - Follow [GitHub](http://twitter.com/githubstatus) and Create/Add it to a `Stat157` list
  - Sign-up for a [Feedly](http://feedly.com) account
    - Add `blog.feedly.com` to your Feedly subscriptions
    - Add `github.com/blog` to your Feedly subscriptions
    - Add `planet.pidgin.im` **and** `adium.im/blog` to your Feedly subscriptions (even if you installed only one, you should be aware of news and updates that may affect your collaborators).
    - Follow https://twitter.com/freenodestaff and add it to your `Stat157` list
    - Add `blog.freenode.net` to your Feedly subscriptions

Tasks
-----

**VirtualBox**
  - Download & Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  - Download Ubuntu Server 13.04, [Raring Ringtail](http://releases.ubuntu.com/raring/)
    - Choose the download option under Server Install Image: 64-Bit PC (AMD64) server install image

**Creating a Virtual Machine**
  - Create a new virtual machine for Ubuntu Server 13.04 in VirtualBox
    - Name 'Stat157' and select _Linux, Ubuntu 64-Bit_ from drop down menus
![selecting names and drop down menu items](https://raw.github.com/lauraccunningham/course-set-up/master/images/1%20creatingComputerInVirtualBox.stat157.png)
    - _Make sure to be aware of your individual machine's hard drive space_
    - **Note**: For Mac Users
      - Finder > Preferences
        - Check your Hard Disk Box is checked
        - Right click Hard Drive Icon on Desktop, click 'Get Info' and Check Capacity
![setting you memory for 1G](https://raw.github.com/lauraccunningham/course-set-up/master/images/2%20increaseTo1GofData.png)
      - Select the Ubuntu Server Image from your downloads folder
      - Accept _MOST_ Defaults for VirtualBox
        - _Not All Defaults are Correct for the Machine we are Setting Up_
          - For a few of the sections in the **!! Partition Disk Section**, we need to change the default
            - The first instance should be changed to <Yes> when asking about writing changes to disks and configuring LVM
![first unaccepted default](https://raw.github.com/lauraccunningham/course-set-up/master/images/4%20doNotAcceptDefault.time1.png)
            - The second should also be changed to <Yes> regarding writing changes to disks
![second unaccepted default](https://raw.github.com/lauraccunningham/course-set-up/master/images/5%20changeDefault,%20time2.png)

    - **Note**: Left ⌘ ( [Command Key](http://en,wikipedia.org/wiki/Comman_key) ) directly refers to the command key ⌘ left of your space bar on the keyborard (Mac Computer Specific). 
    - While using VirtualBox, the Auto Capture feature will be controlled with this Left ⌘ function
        By pressing Left ⌘ you will be able to unlock and lock the auto capture feature with keyboard and mouse
                 ![setting you memory for 1G](https://raw.github.com/lauraccunningham/course-set-up/master/images/3%20importantToLKnowAbout.virtualBoxAutoCaptureFeature%20hitLeftCommandToReleaseMouseAndKeyBoard.png)