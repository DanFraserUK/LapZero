# Changelog

What's new in each LapZero release, newest first.

## v2026.10.27.1

- New Overview page: the Proton build iRacing runs on, the iRacing install, its prefix, Steam and LapZero, at a glance.  It looks them up when you click Look up.
- Setup lists your Steam libraries with their free space when iRacing needs installing, suggests one, and opens Steam's install window to pick it in.
- Closing LapZero while a program installs no longer crashes it.  Closing stops everything LapZero started, including the installer.
- Stop now stops setup's Proton build download.
- Fixed: the launch options check said they didn't match when you'd added settings of your own in front, like `PROTON_ENABLE_HIDRAW` for a Simagic base.  Those are kept now, and in the text to copy.
- Fixed: setup could wait forever when iRacing was installed to another Steam library.
- Clearer messages when a package install fails, and on RHEL-based systems.

## v2026.10.27

- When a newer LapZero Proton build is out, a teal note in the sidebar says so.  Its page shows what's changed, downloads it only when you click, installs it beside your current build, and shows you how to switch iRacing to it in Steam.
- The update page lists what's new in every version since yours, so you can see why it's worth updating.

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
