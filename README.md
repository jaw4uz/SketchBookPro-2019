# SketchBookPro-2019

I have changed from doing a stand alone munki Installer to using the autopkg recipes by
moofit here https://github.com/autopkg/moofit-recipes/tree/master/Autodesk. the scripts will not
be updated.

AutoDesk SketchBook Pro 2019 Munki Installer
Make sure you check your product key and serial number they may have changed.

Put the Autodesk_SketchBook_for_Enterprise_2019_Multilingual_MAC_OSX.dmg into your munki repo packages folder

Put the Autodesk_SketchBook_for_Enterprise_2019-1.0.plist into the pkginfo folder

Edit the installer_item_location key to match the location and name of your .dmg

Add your serial number and edit the product key if it is different

Run makecatalogs

