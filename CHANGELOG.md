# Changelog

What's new in each LapZero release, newest first.

## v2026.10.17

- Launch iRacing button at the top of the sidebar.  It's grey until setup's finished, then green to start iRacing.
- Hardware detection now checks each wheel, base and pedal set.  It shows whether the driver's in use, lists any missing packages, and links to the maker's software.  It covers Simagic, MOZA, Fanatec and Logitech so far.  It installs nothing.
- Hardware detection names more models, like the MOZA R3 to R21 and the Logitech G923.
- The setup list keeps the step it's on in view, with the one before and the one after.
- Fixed: the Ubuntu 22.04 and Mint 21 package couldn't start.  It now pulls in qt6-qpa-plugins.  If you're on either, the last release couldn't update itself, so install this one by hand.
- README: "What LapZero Does as Root" now covers updates too, with the commands the updater runs.
