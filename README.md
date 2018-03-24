# firefox_localfiletab

These files should let you change Firefox's behavior so you can display a local file by default when opening a new tab. This solution was proposed by cor-el [here](https://support.mozilla.org/eu/questions/1202974).

## Instructions
1. Copy mozilla.cfg into the location where your Firefox executable resides
2. Edit mozilla.cfg to point to the local file you want to have opened. This should be setting a new value for the newTabUrl variable
3. Where Firefox is installed (e.g. "C:\Program Files\Mozilla Firefox"), there should be a "defaults" folder under it and under that a "pref" folder. Copy local-settings.js into that "pref" folder
4. Restart firefox and it should work!
