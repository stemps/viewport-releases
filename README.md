<!-- This folder seeds the PUBLIC repo stemps/viewport-releases (source stays
     private). CI publishes the DMG as a GitHub Release here and updates
     appcast.xml; GitHub Pages serves the appcast. -->

# Viewport

Mirror a region of your screen to a virtual display you can share in Zoom, Meet,
or Teams — ideal for ultrawide, 5K/6K, and multi-monitor setups where you only
want to share a slice of your desktop.

## Download

**[⬇︎ Download the latest version](https://github.com/stemps/viewport-releases/releases/latest)**

1. Open the downloaded `Viewport-x.y.z.dmg`.
2. Drag **Viewport** into **Applications**.
3. Launch it from Applications. It lives in the menu bar.

The app is signed with a Developer ID and notarized by Apple, so it opens
without a Gatekeeper warning. It updates itself automatically (via Sparkle); you
can also choose **Check for Updates…** from the menu.

## First run

Viewport needs **Screen Recording** permission to capture the region you mirror.
macOS will prompt on first use — approve it in **System Settings › Privacy &
Security › Screen Recording**, then relaunch.

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel Mac

## Notes

Viewport uses private macOS display APIs to create the virtual display. It is
not available on the Mac App Store. It is free to use.
