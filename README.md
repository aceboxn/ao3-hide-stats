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

## To get up and running:
1. Install Tampermonkey browser extension: https://www.tampermonkey.net/.
2. Once installed, you'll see a tiny robot head in the toolbar. Click it, then click "Dashboard".

That will bring up a screen that looks like the below, yet yours will be empty to start.
3. Click the plus sign to the left of "Installed Userscripts" to add the script.
4. That will auto-generate a script boilerplate. You want to delete everything out of there and paste in the script from ao3-hide-stats.txt.
5. Click "File --> "Save" (all the naming happens automatically from the script).

When you're done, your dashboard screen will look like this (two green toggles for enabled)

## Testing out:
1. Go to AO3: https://archiveofourown.org/. You'll note the little red number on the robot icon - this means a script is enabled.
2. If you want to turn it off, click on the robot icon and click the toggle for "AO3 Stats Hiding".
