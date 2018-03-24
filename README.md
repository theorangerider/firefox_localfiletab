# firefox_localfiletab

These files should let you change Firefox's behavior so you can display a local file by default when opening a new tab.

## Instructions
1. Edit mozilla.cfg to point to the local file you want to have opened. This should be setting a new value for the newTabUrl variable
2. Copy mozilla.cfg into the location where your Firefox executable resides
3. Where Firefox is installed (e.g. "C:\Program Files\Mozilla Firefox"), there should be a "defaults" folder under it and under that a "pref" folder. Copy local-settings.js into that folder
4. Restart firefox and it should work!
