---
title: Writing an SD Card Image Using Apple Pi Baker on OS X
subject: SD Card Image
---

**Forward**

Using this option is probably the least error prone, and most straight forward. 
This will not allow you to wipe out your OS drive. This option will however wipe out your SD card. 
Be sure to backup any important files prior to running this.

---
**Install Apple Pi Baker**

1. Download Apple Pi Baker from http://www.tweaking4all.com/hardware/raspberry-pi/macosx-apple-pi-baker/
2. Unpack the program, and put the executable in your applications folder

---
**The ev3dev image**

    Possible Pitfall: 
    If you do like I did and accidently use the evb image version for your ev3, 
    then you're not going to have a good day.

1. You should have already downloaded the latest version, see also http://www.ev3dev.org/docs/getting-started/#step-1-download-the-latest-ev3dev-image-file
2. Find and unpack the downloaded zip file
3. Remember where this file is currently located

---
**Bake the image onto your SD card**

1. Insert your SD card into your computer's SD card reader
2. Launch Apple Pi Baker
3. When it loads it should list your SD card as an available option under the PI crust section. Select the SD card.
4. In the IMG recipe section click the "..." button to locate and select the unpacked img file of your choice
5. click "Restore Backup"
