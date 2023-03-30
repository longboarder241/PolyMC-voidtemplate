# PolyMC-voidtemplate
Void Linux is an amazing OS however the devs keep trying to inject politics into every part of the os making dealing with the package manager completely insufferable.  This resulted in the deletion of the PolyMC template  so archived here was the last template made for the OS.  If you have reccommendations or adjustments that need to be made to this submit a pull request.
#Instructions
-rename the folder to PolyMC (Case Sensitive)
-go into cloned void-packages/srcpkgs folder and delete current PolyMC folder, the current one just redirects
# copy the folder ungoogled-chromium-void/ungoogled-chromium to void-packages/srcpkgs/
$ ./xbps-src pkg ungoogled-chromium
$ xbps-install -vR hostdir/binpkgs ungoogled-chromium
