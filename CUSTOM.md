My changes to the base source code
----------------------------------

This repo is based on whatever was the HEAD in the main Git repo on Suckless. I'll
sync it every now and then.

* Use the Jellybeans color scheme.
* Added an Arch Linux PKGBUILD that pulls this repo and builds. I fixed some issues with the PKBUILD from the AUR to work how I want.
* Playing with the terminfo stuff (don't think I actually changed anything in the end).
* Merged the transparency patch from the web page and tweaked it to work on the Git version instead of 0.5.
  * I added a kinda ugly hack to make transparency disabled by default, enable it with the new -z flag
* Added this file!
