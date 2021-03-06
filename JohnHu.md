## 1/5 - 1/9 ##
### Last Week ###
* [hash launch]
  - [Bug 1113495](http://bugzil.la/1113495) - [Stingray][Smart-system] Accept specified URL from home on opening app (landed)
  - [Bug 1113499](http://bugzil.la/1113499) - [Stingray][Smart-home] Open app with specified hash/URL (landed)
* [Partner's Requirements]
  - [Bug 1115350](http://bugzil.la/1115350) - [Stingray] no wallpaper is necessary for smart-home (fixed)
  - [Bug 1100892](http://bugzil.la/1100892) - [Stingray] bootup with transparency background (fixed)
  - [Bug 1115351](http://bugzil.la/1115351) - [Stingray][Home] video element is hidden by overlayed home (fixed)
* [Search Bar]
  - [Bug 1115273](http://bugzil.la/1115273) - [Stingray][smart-home/smart-system] Implement opening search bar (landed)
* [Partner Meeting and Offline Supporting]
  - Dashboard
  - Home
  - App start-up dialog
    -[Bug 1119655](http://bugzil.la/1119655) - [Stingray] show a dialog while opening some apps (fixed)

### This Week ###
* [Partner Blocker]
  - [Bug 1118641](http://bugzil.la/1118641) - [Stingray][Home] the app name in card will be moved to top-right slightly when we focus it (r+ but not landed, ETA: 1/16)
  - [Bug 1105650](http://bugzil.la/1105650) - [Stingray] Apply visual of button on app-deck list (steal from dwi2, WIP got, ETA: 1/16)
* Other Bugs:
  - [Bug 1119748](http://bugzil.la/1119748) - [Stingray] use keydown to change the focus (r+, but not landed)
  - [Bug 1120342](http://bugzil.la/1120342) - [Stingray] build failed because of jshint error- missing semicolon

----------
## 12/15 - 12/19 ##
### Last Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - [Bug 1111416](http://bugzil.la/1111416) - [Stingray] tv build unable to copy web components in tv_shared) (landed)
  - reviewing:
    - [Bug 1110652](http://bugzil.la/1110652) - [Stingray] use interactive notification to show desktop-notification
    - [Bug 1111414](http://bugzil.la/1111414) - [Stingray] create UI for and apply visual to interactive notification
* [Home as Overlay]
  - [Bug 1107950] - [Stingray][System] homescreen app is shown as overlay on top of an alive app while press home. (reviewing)
### This Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - rebase and land code
  - [Bug 1114397] - [Stingray] Use keyboard to move the focus between notification buttons
* Bug:
  - [Bug 1114399] - [Stingray][Home] settings button group isn't collapsed consistently while losting focus

----------
## 12/08 - 12/12 ##
### Last Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101371](http://bugzil.la/110371) - [Stingray][home] apply visual spec to card list
  - Rebased and Land the Code
    - [Bug 1105576](http://bugzil.la/1105576) - [Stingray][home] update visual of smart home to meet visual spec v2
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer
    - [Bug 1101369](http://bugzil.la/1101369) - [Stingray][home] apply visual to information block
### This Week ###
* [Interactive Notifications]
  - Meta Bug: [Bug 1109493](http://bugzil.la/1109493)
    - [Bug 1111416](http://bugzil.la/1111416) - [Stingray] tv build unable to copy web components in tv_shared)
    - [Bug 1110652](http://bugzil.la/1110652) - [Stingray] use interactive notification to show desktop-notification

----------
## 12/01 - 12/05 ##
### Last Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer)
    - [Bug 1105576](http://bugzil.la/1105576) - [Stingray][home] update visual of smart home to meet visual spec v2
* [Landing app]
  - [Bug 1107976](http://bugzil.la/1107976) - [Stingray][System] handle app to landing app opening.
    - landing app will be only deck in the past. But if we want to support normal app as landing app, it may be opened in app deck.
* Discussions
  - TV testing environment
    - discuss with Alex and have a WIP patch which only works at Ubuntu box
    - [Bug 1107759](http://bugzil.la/1107759) - Support resizing b2g desktop window
  - IAC
    - discuss with Ehsan
      - He will work on a XHR server for service worker in the future. ETA is still undefined.

### This Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1101371](http://bugzil.la/1101371) - Support resizing b2g desktop window
* discuss and work on notifications
----------

## 11/24 - 11/28 ##

update skipped
----------

## 11/17 - 11/21 ##

### Last Week ###
* [TV Settings]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
      - landed
    - [Bug 1093530](http://bugzil.la/1093530) - [Stingray][System] make inline activity be transparent in background
      - landed
    - [Bug 1094069](http://bugzil.la/1094069) - [Stingray][Settings] implement option menu
      - landed
    - [Bug 1100282](http://bugzil.la/1100282) - [Stingray][System] only allow smart-settings app to handle configure activity
      - landed
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1102142](http://bugzil.la/1102142) - [Stingray][home] create circle-button and use it in Home's search button
      - reviewing

### This Week ###
* [Apply Visual to Home]
  - Meta Bug: [Bug 1101329](http://bugzil.la/1101329)
    - [Bug 1102153](http://bugzil.la/1102153) - [Stingray][home] create button-group and apply to settings button in home app
    - [Bug 1101369](http://bugzil.la/1101369) - [Stingray][home] apply visual to information block
    - [Bug 1101373](http://bugzil.la/1101373) - [Stingray][home] apply visual spec to filter (footer)
    - [Bug 1101371](http://bugzil.la/1101371) - [Stingray][home] apply visual spec to card list
  - maybe file a bug to add web component support in tv_shared folder
----------

## 11/10 - 11/14 ##

### Last Week ###
* [TV Setting]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1092934](http://bugzil.la/1092934) - [Stingray] Create settings app for changing landing app
      - landed
    - [Bug 1093436](http://bugzil.la/1093436) - [Stingray][Home] move libraries to tv-shared folder
      - landed
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
      - reviewing
    - [Bug 1093534](http://bugzil.la/1093534) - [Stingray][Settings] add settings list to settings app
      - landed

### This Week ###
* Partner Meeting
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/
  - https://docs.google.com/a/mozilla.com/spreadsheets/d/19BPa6GCxPPoLZxy_r1tJSPG4JZVUCbpSKwSXYjJ5Jbg/edit#gid=0

------------

## 11/03 - 11/07 ##

### Last Week ###
* Prepare materials for the discussion with partners
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/

* Replying partners' emails
  - Card UI

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.

### This Week ###
* [TV Setting]
  - Meta Bug: [Bug 1067793](http://bugzil.la/1067793)
    - [Bug 1092934](http://bugzil.la/1092934) - [Stingray] Create settings app for changing landing app
    - [Bug 1093436](http://bugzil.la/1093436) - [Stingray][Home] move libraries to tv-shared folder
    - [Bug 1093529](http://bugzil.la/1093529) - [Stingray] link home app to settings app
    - [Bug 1093534](http://bugzil.la/1093534) - [Stingray][Settings] add settings list to settings app

------------

## 10/27 - 10/31 ##

### Last Week ###
* [TV System]
  - [Bug 1090808](http://bugzil.la/1090808) - [Stingray] lazy load smart-system's modules
    - no significant improvement at flame device.
    - patch can be found at:
      - https://github.com/huchengtw-moz/gaia/tree/bug-1098080-lazy-load-pr
  - [Bug 1090810](http://bugzil.la/1090810) - [Stingray] add SettingsCache to smart system
    - PR ready and waiting for review result.
    - https://github.com/mozilla-b2g/gaia/pull/25641
  - [Bug 1090806](http://bugzil.la/1090806) - [Stingray] remove useless file from smart-system
    - touch_forwarder, secure_*, and system_dialog* had been removed
    - landed.
  - [Bug 1090822](http://bugzil.la/1090822) - [Stingray] trusted_ui in smart system should lock screen in default mode. 
    - landed.
  - A SettingsCache with async_storage backend gives the most improvement.
    - https://github.com/huchengtw-moz/gaia/tree/bug-1090810-local-storage
    - It uses async_storage instead of local storage and the branch name is a typo.
  - The overall performance report can be found at:
    - https://docs.google.com/a/mozilla.com/spreadsheets/d/19BPa6GCxPPoLZxy_r1tJSPG4JZVUCbpSKwSXYjJ5Jbg/edit#gid=0

### This Week ###

* Prepare materials for the discussion with partners
  - https://wiki.mozilla.org/FirefoxOS/Stingray/SmartScreen/

* Replying partners' emails
  - Card UI

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.

## 10/20 - 10/24 ##

### Last Week ###
* [TV System]
  - Done locally, revice patch according to review's opinions
    - [Bug 1074040](http://bugzil.la/1074040) - [Stingray] Default landing deck
      - [PR](https://github.com/mozilla-b2g/gaia/pull/25247)
  - Use SettingsCache to boost up boot-up time.
    - [branch](https://github.com/huchengtw-moz/gaia/tree/bug-1074040-settings-cache)
  - Try to lazy load modules
    - https://tw-dev-eng.etherpad.mozilla.org/151

This Week

* [TV System]
  - Lazy loading files
  - check the performance

* [TV Setting]
  - [Bug 1067793](http://bugzil.la/1067793) - [Stingray] Customization on the default landing card/deck
    - add a standalone settings app and modify system app to support special UI for it.
