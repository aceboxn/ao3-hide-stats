# ao3-hide-stats
Script to hide all user stats, such as comments, kudos, hits, bookmarks, from browsing on Archive of Our Own (AO3).

Across all AO3 pages, hides the following:
- comments
- kudos
- views
- bookmarks
- comments button
- inbox button

## View with stats hidden versus standard AO3
### With stats hidden
![After](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/10.png)
### Standard AO3
![Before](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/9.png)

## To get up and running:
1. Install Tampermonkey browser extension: https://www.tampermonkey.net/.

2. Once installed, you'll see a tiny robot head in the toolbar. Click it, then click "Dashboard".

![2a](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/1.png)

![2b](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/2.png)

That will bring up a screen that looks like the below, yet yours will be empty to start.

3. Click the plus sign to the left of "Installed Userscripts" to add the script.

![3](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/3.png)

4. That will auto-generate a script boilerplate. You want to delete everything out of there and paste in the script from [AO3 Stats Hiding.txt](https://github.com/aceboxn/ao3-hide-stats/blob/master/AO3%20Stats%20Hiding.txt).

![4](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/4.png)

5. Click "File --> "Save" (all the naming happens automatically from the script).

![5a](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/5.png)

When you're done, your dashboard screen will look like this (two green toggles for enabled)

![5b](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/6.png)

## Testing out:
1. Go to AO3: https://archiveofourown.org/. You'll note the little red number on the robot icon - this means a script is enabled.

![1](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/7.png)

2. If you want to turn it off, click on the robot icon and click the toggle for "AO3 Stats Hiding".

![2](https://github.com/aceboxn/ao3-hide-stats/blob/master/statshiding/8.png)
