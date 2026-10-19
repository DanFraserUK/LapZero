# Changelog

What's new in each LapZero release, newest first.

## v2026.10.19.1

- While iRacing is running, LapZero waits.  Setup, checks, installing programs and updates hold off until it closes, and a banner says why.  Its Close iRacing button asks iRacing to close, and forces it if it's still open after 15 seconds.
- Launch iRacing waits while setup or an install is running.
- Hardware detection finds SimPro Manager 3 when it's on the Additional programs page.
- Fixed: a program added with Find programs already installed could be started with a stray empty argument, which also broke its desktop shortcut.

## v2026.10.19

- Fixed: with iRacing in your Steam library but not installed, setup said it wasn't in your library at all.  It now asks whether it's in your library or you have a key to redeem, and only opens the key window if you have a key.

## v2026.10.18.3

- The Launch iRacing button dims to blue while iRacing is starting or running, and does nothing until it closes.

## v2026.10.18.1

- The Updates page puts Update now first, then says step by step what it does, with the exact command it runs to install.

## v2026.10.18

- Updates don't download anything until you click Update now.  The sidebar says when one's available, and the button shows the download's progress.

## v2026.10.17

- Launch iRacing button at the top of the sidebar.  It's grey until setup's finished, then green to start iRacing.
- Hardware detection now checks each wheel, base and pedal set.  It shows whether the driver's in use, lists any missing packages, and links to the maker's software.  It covers Simagic, MOZA, Fanatec and Logitech so far.  It installs nothing.
- Hardware detection names more models, like the MOZA R3 to R21 and the Logitech G923.
- The setup list keeps the step it's on in view, with the one before and the one after.
- Fixed: the Ubuntu 22.04 and Mint 21 package couldn't start.  It now pulls in qt6-qpa-plugins.  If you're on either, the last release couldn't update itself, so install this one by hand.
- README: "What LapZero Does as Root" now covers updates too, with the commands the updater runs.
