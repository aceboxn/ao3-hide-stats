# AO3 Stats Hiding
Script to hide all user stats from browsing on Archive of Our Own (AO3). Provides clean interface to write and browse without seeing popularity of works.

Across all AO3 pages, hides the following:
- comments
- kudos
- views
- bookmarks
- comments button
- inbox button

**NOTE:** If you still wish the inbox to be visible, delete the following text in AO3 Stats Hiding.txt: a[href="/users/yourusername/inbox"]{display:none !important;}

## View with stats hidden versus standard AO3
### With stats hidden
![After](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/10.png)
### Standard AO3
![Before](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/9.png)

## To get up and running:

Prequisite: Desktop browser capable of running Tampermonkey (supports most modern browsers).

1. Install Tampermonkey browser extension: https://www.tampermonkey.net/.

2. Once installed, you'll see a tiny robot head in the toolbar. Click it, then click "Dashboard".

![2a](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/1.png)

![2b](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/2.png)

That will bring up a screen that looks like the below, yet yours will be empty to start.

3. Download the [AO3 Stats Hiding.txt](https://github.com/aceboxn/ao3-hide-stats/blob/master/AO3%20Stats%20Hiding.txt) file from this GitHub repo. Search for the word yourusername and replace it with your username as it appears on AO3. You can find how your AO3 username appears in urls by going to https://archiveofourown.org and clicking on My Dashboard. Your username will appear in the url bar after /users/.

Search for yourusername:

![3a](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/11.png)

Replace it with your AO3 username as it appears in the URL bar (in this case, appears as sonshineandshowers).

![3b](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/12.png)

4. Click the plus sign to the left of "Installed Userscripts" to add the script.

![4](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/3a.png)

5. That will auto-generate a script boilerplate. You want to delete everything out of there and paste in the AO3 Stats Hiding.txt script you downloaded and modified in step 3.

![5](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/4.png)

6. Click "File --> "Save" (all the naming happens automatically from the script).

![6a](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/5a.png)

When you're done, your dashboard screen will look like this (green toggle for enabled)

![6b](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/6.png)

## Testing out:
1. Go to AO3: https://archiveofourown.org/. You'll note the little red number on the robot icon - this means a script is enabled.

![1](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/7.png)

2. If you want to turn it off, click on the robot icon and click the toggle for "AO3 Stats Hiding".

![2](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/8.png)

## Bugs & New Feature Requests

If you find something not working as expected or have a new feature request, please feel free to open an issue or message me on tumblr: https://sonshineandshowers.tumblr.com/
