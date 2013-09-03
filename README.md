homework-01
===========
Kimberly Le
===========
Due September 03, 2013

Here are the next steps for the homework assignment that you should complete by Tuesday's class so that everyone is on the same page with virtualbox and Ubuntu Server installed.

Much thanks to Laura Cunningham who helped me create this assignment today.

Tasks
-----

- [ ] Download VirtualBox https://www.virtualbox.org/wiki/Downloads
- [ ] Install VirtualBox
- [ ] Download `.iso` for Ubuntu Server 13.04 (Raring Ringtail) http://releases.ubuntu.com/raring/
      **NOTE: Even though you may be on a Mac, you should download the 64-bit PC (AMD64) version for running inside VirtualBox.**
      - Choose the download option under Server Install Image: [64-bit PC (AMD64) server install image](http://releases.ubuntu.com/raring/ubuntu-13.04-server-amd64.iso)
      - A **faster** way to download the `.iso` is to use [64-bit PC (AMD64) server install image TORRENT](http://releases.ubuntu.com/raring/ubuntu-13.04-server-amd64.iso.torrent)
- [ ] Create a new virtual machine for Ubuntu Server 13.04 in Virtual Box
      - Name 'Stat157' and select Linux, Ubuntu 64-bit from drop down menus
      ![selecting names and drop down menu items](https://raw.github.com/lauraccunningham/homework-01/master/images/1%20creatingComputerInVirtualBox.stat157.png)
      - Make sure to be aware of your individual machine's hard drive space
            - For Mac Users:  Finder > Preferences
                              Check your Hard Disk box is checked
                              Right click Hard Drive icon on Desktop, click 'Get Info' and check capacity
      ![setting you memory for 1G](https://raw.github.com/lauraccunningham/homework-01/master/images/2%20increaseTo1GofData.png)
      - Select the Ubuntu Server Image from your downloads folder
      - Accept Defaults for VirtualBox
      - ** Note:  Left ⌘ (Command Key, http://en.wikipedia.org/wiki/Command_key) directly refers to the ⌘ key left of your space bar on the keyboard. **
      ![setting you memory for 1G](https://raw.github.com/lauraccunningham/homework-01/master/images/3%20importantToLKnowAbout.virtualBoxAutoCaptureFeature%20hitLeftCommandToReleaseMouseAndKeyBoard.png)
            - Becareful for accepting all defaults for setting up the virtual machine.  There are two instances you should make sure you are changes during this process
                  ![first unaccepted default](https://raw.github.com/lauraccunningham/homework-01/master/images/4%20doNotAcceptDefault.time1.png)
                  ![second unaccepted default](https://raw.github.com/lauraccunningham/homework-01/master/images/5%20changeDefault,%20time2.png)

- [ ] Ensure [hardware-level
  virtualization](http://en.wikipedia.org/wiki/X86_virtualization)
  support is enabled in your BIOS. If you receive a warning from
  VirtualBox that "VT-x/AMD-V hardware acceleration has been enabled,
  but is not operational. Please ensure that you have enabled
  VT-x/AMD-V properly in the BIOS of your host computer." Then you
  will need to reboot your computer to enter the BIOS settings screen,
  for example here is what was required for an [HP
  Pavilion](http://h30434.www3.hp.com/t5/Other-Notebook-PC-Questions/HP-Pavilion-dv6-enabling-VT-x-in-BIOS/td-p/656627)
  computer. Instructions for your make/model will be similar, but may
  not be exactly what's available here. Most computers within the last
  couple of years support hardware virtualization, but even some as
  recent as 2011 do not have it, so if you are not able to find the
  option to enable, then please contact your instructors to explore
  other available options.
