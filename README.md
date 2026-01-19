# sprocketAR1S

# Introduction
sprocketAR1S is a heavily modified evolution of [Paul Sauro](https://github.com/Olsro/)’s [sprocketModern](https://themes.rockbox.org/index.php?themeid=3549&target=ipodmini2g) theme, featuring a refined WPS with dedicated sleep-timer iconography, a fresh new lockscreen, and a dynamic bar at the bottom of the Main Menu that intelligently toggles between track metadata and system time. Powered by the Rockbox-Mix font for full multi-language support
- sprocketAR1S comes in two device versions:
  - [iPod Mini](https://themes.rockbox.org/index.php?themeid=3954)
  - [iPod 4G (Monochrome)](https://themes.rockbox.org/index.php?themeid=3955)

# Changelog

### Font Changes
- Replaced Adobe Helvetica Bold fonts with Nimbus font (10pt for menus, 35pt and 19pt for lock screen)
- Uses Rockbox-Mix font (14pt) to support all language characters

### Lock Screen Enhancement
- Added a new lock screen feature with clock display
- Two display modes:
  - **With Album Art**: Shows album art (70x70 on Mini, 90x90 on 4G) with time, day, and date
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

### Technical Improvements
- Better conditional logic for viewport display management
- Optimized image loading and viewport declarations
- Improved status detection for lock screen activation
- Enhanced volume indicator mapping

## Device-Specific Dimensions

### iPod Mini (138x110)
- Cover art: 55x55 (compact view), 70x70 (lock screen)
- Progress bar: 132x8
- Main viewport: 138x73 (with Now Playing section at bottom)

### iPod 4G (160x128)
- Cover art: 70x70 (compact view), 90x90 (lock screen)
- Progress bar: 154x8
- Main viewport: 160x89 (with Now Playing section at bottom)
  
# Preview
## iPod Mini
![Alt text](Img/MiniWPSCA.png?raw=true "MiniWPSCA")
![Alt text](Img/MiniWPS.png?raw=true "MiniWPS")
![Alt text](Img/MiniMenu.png?raw=true "MiniMenu")
![Alt text](Img/MiniLockCA.png?raw=true "MiniLockCA")
![Alt text](Img/MiniLock.png?raw=true "MiniLock")

## iPod 4G (Monochrome)
![Alt text](Img/4GWPSCA.png?raw=true "4GWPSCA")
![Alt text](Img/4GWPS.png?raw=true "4GWPS")
![Alt text](Img/4GMenu.png?raw=true "4GMenu")
![Alt text](Img/4GLockCA.png?raw=true "4GLockCA")
![Alt text](Img/4GLock.png?raw=true "4GLock")
