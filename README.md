homework-01
===========

Due September 03, 2013

Laura Cunningham


Tasks
-----

- [ ] Download VirtualBox https://www.virtualbox.org/wiki/Downloads
- [ ] Install VirtualBox
- [ ] Download Ubuntu Server 13.04 (Raring Ringtail) http://releases.ubuntu.com/raring/
      - Choose the download option under Server Install Image: 64-bit PC (AMD64) server install image
- [ ] Create a new virtual machine for Ubuntu Server 13.04 in Virtual Box
      - Name 'Stat157' and select Linux, Ubuntu 64-bit from drop down menus
      ![selecting names and drop down menu items](https://raw.github.com/lauraccunningham/course-set-up/master/images/1%20creatingComputerInVirtualBox.stat157.png)
      - Make sure to be aware of your individual machine's hard drive space
            - For Mac Users:  Finder > Preferences
                              Check your Hard Disk box is checked
                              Right click Hard Drive icon on Desktop, click 'Get Info' and check capacity
      ![setting you memory for 1G](https://raw.github.com/lauraccunningham/course-set-up/master/images/2%20increaseTo1GofData.png)
      - Select the Ubuntu Server Image from your downloads folder
      - Accept _MOST_ Defaults for VirtualBox
            - Not all defaults are correct for the machine we are setting up
              For a few of the sections in the !! Partition Disk section, we need to change the default
              The first instance should be changed to <Yes> when asking about writing changes to disks and configuring LVM
                  ![first unaccepted default](https://raw.github.com/lauraccunningham/course-set-up/master/images/4%20doNotAcceptDefault.time1.png)
              The second should also be changed to <Yes> regarding writing changes to disks
                  ![second unaccepted default](https://raw.github.com/lauraccunningham/course-set-up/master/images/5%20changeDefault,%20time2.png)
      - ** Note: Left ⌘ (Command Key, http://en,wikipedia.org/wiki/Comman_key) directly refers to the command key ⌘ left of your space bar on the keyborard (Mac Computer Specific). ** 
      - While using VirtualBox, the Auto Capture feature will be controlled with this Left ⌘ function
        By pressing Left ⌘ you will be able to unlock and lock the auto capture feature with keyboard and mouse
                 ![setting you memory for 1G](https://raw.github.com/lauraccunningham/course-set-up/master/images/3%20importantToLKnowAbout.virtualBoxAutoCaptureFeature%20hitLeftCommandToReleaseMouseAndKeyBoard.png)
