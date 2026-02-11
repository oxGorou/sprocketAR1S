# sprocketAR1S

# Introduction
sprocketAR1S is a heavily modified evolution of [Paul Sauro](https://github.com/Olsro/)’s [sprocketModern](https://themes.rockbox.org/index.php?themeid=3549&target=ipodmini2g) theme, featuring a refined WPS with dedicated sleep-timer iconography, a fresh new lockscreen, and a dynamic bar at the bottom of the Main Menu that intelligently toggles between track metadata and system time. Powered by the Rockbox-Mix font for full multi-language support
- sprocketAR1S comes in two device versions:
  - [iPod Mini](https://themes.rockbox.org/index.php?themeid=3954)
  - [iPod Monochrome (Gen 1-4)](https://themes.rockbox.org/index.php?themeid=3955)

# Reddit
[Introduction Post](https://www.reddit.com/r/ipod/comments/1qzg3gm/introducing_sprocketar1s_theme_for_ipod_mini_ipod/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
# Changelog

### Font Changes
- Replaced Adobe Helvetica Bold fonts with Nimbus font (10pt for menus, 35pt and 19pt for lock screen)
- Uses Rockbox-Mix font (14pt) to support all language characters

### Lock Screen Enhancement
- Added a new lock screen feature with clock display
- Two display modes:
  - **With Album Art**: Shows album art (70x70 on Mini, 88x88 on 4G) with time, day, and date
  - **Without Album Art**: Full-screen clock display with centered time, day, and date
- Shows "Scroll To Unlock" message when device is unlocked
- Lock screen appears when device is locked in main menu and playback is active 

### Status Bar Improvements
- Simplified title bar menu text displays
- Optimized battery percentage display with better spacing
- Adjusted HDD activity indicator positioning

### Now Playing Information
- Added a dedicated Now Playing section at the bottom of the status bar
- Displays current track information (title, artist, album, year) in a scrolling format
- Shows playback status icon (play/pause/stop/etc.)
- Alternates with clock display when playback is stopped or sleep timer is active

### Progress Bar and Timer
- Added Sleep Timer icon to indicate when the function is enabled
- Timer icon positioning adjusts dynamically based on repeat/shuffle/crossfade status
- Clock display shows either sleep timer countdown or current time

### Viewport Adjustments
- Main info viewport resized to accommodate new Now Playing section
- Status bar separator repositioned (at y=14 for Mini, with additional separator at y=91/109 for menus)
- Optimized layout spacing across all screen elements

### WPS Enhancements
- WPS now uses its own status bar (`%wd`) instead of relying on SBS
- Improved playlist position display with dynamic width adjustment based on active features
- Simplified artist/album display using directory fallbacks
- Removed alternating "Clock:" and "Sleep:" labels for cleaner display

## Device-Specific Dimensions

### iPod Mini (138x110)
- Cover art: 55x55 (compact view), 70x70 (lock screen)
- Progress bar: 132x8
- Main viewport: 138x73 (with Now Playing section at bottom)

### iPod Monochrome (Gen 1-4) (160x128)
- Cover art: 70x70 (compact view), 88x88 (lock screen)
- Progress bar: 154x8
- Main viewport: 160x89 (with Now Playing section at bottom)
  
# Preview
## iPod Mini
![Alt text](Preview/Mini_WPSCA.png?raw=true "MiniWPSCA")
![Alt text](Preview/Mini_WPS.png?raw=true "MiniWPS")
![Alt text](Preview/Mini_MainMenu.png?raw=true "MiniMenu")
![Alt text](Preview/Mini_LockCA.png?raw=true "MiniLockCA")
![Alt text](Preview/Mini_Lock.png?raw=true "MiniLock")

## iPod Monochrome (Gen 1-4)
![Alt text](Preview/4G_WPSCA.png?raw=true "4GWPSCA")
![Alt text](Preview/4G_WPS.png?raw=true "4GWPS")
![Alt text](Preview/4G_MainMenu.png?raw=true "4GMenu")
![Alt text](Preview/4G_LockCA.png?raw=true "4GLockCA")
![Alt text](Preview/4G_Lock.png?raw=true "4GLock")
