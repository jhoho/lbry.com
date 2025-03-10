---
title: How do I backup and/or migrate my LBRY data?
category: troubleshooting
---

We have covered LBRY wallet backup procedures in the guide [here](/faq/how-to-backup-wallet), but the purpose of this guide will be how to backup and/or migrate all your LBRY data which includes your downloads, hosted data, wallet and other settings. To follow this guide effectively, it's a good idea to familiarize yourself with LBRY [working directories](/faq/lbry-directories), especially the `lbrynet` and `lbryum` folders. ***In the case of Mac OS, the `lbrynet` folder contents are stored inside the `LBRY` folder as detailed on the directories page.***

In addition to those two directories, users may also want to copy their LBRY downloads - this directory is normally set to your local Downloads folder but can also be configured via the LBRY app.  To check your LBRY Downloads directory, open the LBRY app and go to Settings - it is listed in the `Download Directory` section.  If you chose not to copy over your Downloads folder, the content could be regenerated from the data in your `lbrynet` folder at a later time via the LBRY app.

To summarize, the main directories to consider when backing up or migrating a LBRY installation are as follows:
##### - LBRY Wallet - `lbryum`
##### - Data/Settings - `lbrynet` (`LBRY` on Mac)
##### - File Downloads - Typically your local Downloads directory (Check settings in LBRY app).

##### *\*Please note: both the Data/Settings and File Downloads directories may be large if you have downloaded lots of LBRY content*

### How do I backup all LBRY related data?

1. Refer to the LBRY [working directories](/faq/lbry-directories) to find your data folders
2. Make a copy of the `lbrynet` (`LBRY` folder if on Mac) folder to a secure location
3. Make a copy of the `lbryum` folder to a secure location
4. Make a copy of your LBRY Downloads directory to a secure location

### How do I migrate all LBRY related data to a new installation?

1. Install [LBRY](/get) onto the target PC. Close LBRY after the initial startup. LBRY minimizes to the system tray by defailt, so make sure that is is completely closed.
2. Copy the `lbrynet` folder from the previous section into the appropriate [location](/faq/lbry-directories) on your new installation.
3. Copy the `lbryum` folder from the previous section into the appropriate [location](/faq/lbry-directories) on your new installation.
4. Copy your LBRY Downloads from the previous section into the appropriate location.
5. Start LBRY on the new PC.
6. Sign back into LBRY via your Email by going to the wallet (bank icon in the top right) and then accessing the "Rewards" tab.
7. Verify wallet balance, Downloads, Published files and Rewards eligibility.

*\*Note 1: Do not run two instances of LBRY from the same wallet, this is unsupported.*

*\*Note 2: If you get startup errors after this procedure: check if the `daemon_settings.yml` file from the `lbrynet` folder points to the correct LBRY file download directory. If it does not, edit the file with correct file path and restart the app. You can view and edit this file with any text editor.*

### How do I backup just my wallet?

Please see [our FAQ on wallet backup procedures](https://lbry.com/faq/how-to-backup-wallet)

### I'm in need of some assistance, can you help?

Of course, we are always here to help! Check out our [help page](/faq/how-to-report-bugs) on how to reach us.  If you are having trouble starting LBRY after migration, sending us your [log file](/faq/how-to-find-lbry-log-file) will expedite the resolution.
