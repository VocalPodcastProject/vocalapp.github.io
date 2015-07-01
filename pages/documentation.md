---
title: Documentation
permalink: /documentation/
---

# Getting Started

## Building Your Library

When you first open Vocal you will see a welcome screen asking how you would like to build your library. This is done either by adding a single feed or importing multiple feeds at once from a subscriptions file.

<img src="{{ site.baseurl }}/images/documentation/getting-started.png" />

---

<div class="float-left clear half"><img src="{{ site.baseurl }}/images/documentation/add-podcast.png" /></div>

If you want to add a single feed to get started, simply select the 'Add a New Feed' option. Enter the feed address into the text field and press the 'Add Podcast' button. At the top of the app you will see a message that it is adding the feed to the library. Once it completes the welcome screen will disappear and you will be taken to your library. If there was an error for some reason you will be notified and allowed to try again.

<div class="float-right clear half"><img src="{{ site.baseurl }}/images/documentation/import-subscriptions.png" /></div>

If you want to add multiple feeds at the same time, choose the 'Import Subscriptions' option. You will be given a file selection dialog to select a .OPML subscriptions file. This might be a file you have exported from iTunes or another podcast client (including Vocal) or even a file downloaded from the web, such as our starter pack. Select the file by pressing the 'Open' button and Vocal will start building your library. You will see a progress bar at the top of the screen telling your how many new feeds have been added and how many you have left. Please note: if you are importing several feeds at once it could take a few minutes.

If you are new to podcasting, or would just like some suggestions, you can click the 'Check Out the Vocal Starter Pack' button to see [our picks for podcasts you'll probably enjoy](/starter-pack/).

---

## Navigating the Library

The library view features three main areas: a cover art area that is used to select podcast feeds, an episode sidebar that is used to navigate through episodes, and a top bar used for controlling playback, viewing current episode information, and other various app controls.

### Cover Art

<div class="float-right clear half"><img src="{{ site.baseurl }}/images/documentation/cover-art.png" /></div>

This area shows the cover art for all the podcasts currently in the library. It also displays a banner in the top right corner showing how many new, unplayed episodes are available for each podcast.

### Episode Sidebar

<div class="float-left clear half"><img src="{{ site.baseurl }}/images/documentation/sidebar-episodes.png" /></div>

The episode sidebar shows a list of episodes for the currently selected podcast. An icon to the upper left of an episode indicates that it has not yet been played. A star icon indicates that that episode is the one currently being played.

The center contents of an episode tell you the episode name, when it was released, and its description. The icons in the top right give you the options to stream the episode, to download it to your library, and to play it if it has already been downloaded.

The bottom toolbar allows you to mark all episodes as played, to download all episodes, and to hide episodes that you've already played. Additionally, the gear menu allows you select other options such as removing the podcast from the library.

<div class="float-right clear half"><img src="{{ site.baseurl }}/images/documentation/sidebar-context-menu.png" /></div>



If you wish to hide the sidebar you can press the hide button in the top right. Selecting another podcast by clicking on the coverart will make it appear again.

You can also manually flag episodes as played or unplayed or manually delete downloaded files by right-clicking on the episodes and choosing the appropriate action. Advanced users can use the shift and control keys to select multiple episodes for bulk actions.

### Headerbar

<img src="{{ site.baseurl }}/images/documentation/headerbar.png" />

The headerbar contains playback controls on the left, playback and import status in the middle, and additional buttons on the right. The playback controls let you skip forward and backward a set number of seconds in the episode, as well as play and pause.

The status area in the center shows how far into the episode you are. By clicking inside the progress bar you can change your current position in the episode. This area also features a button to view the show notes / description for the episode you're currently listening to. When you add or import podcasts, their status will be displayed here as well.

The refresh button on the right of the headerbar checks for new episodes and adds any that it finds to the library. The add button allows you to add new feeds, either by entering a feed address or by importing subscriptions. Finally, the app menu allows you to set preferences, donate to the project, and export your library.

### Downloads

<div class="float-left clear half"><img src="{{ site.baseurl }}/images/documentation/downloads.png" /></div>

When you click to download an episode, or if the download happens automatically, you will notice that an additional button appears in the headerbar. Clicking it will allow you to see which episodes are downloading, check their progress, and cancel them.

---

# Video Playback

<img src="{{ site.baseurl }}/images/documentation/video-playback.png" />

When you press play on a video, the library view disappears and the video is displayed inside the main window. When the video is not fullscreen you can control playback in the normal manner. If you want to return to the library, simply move your cursor over the video and select the back button in the upper left-hand corner.

When the video is fullscreen playback controls will be available as a bar at the bottom of the video. The return to library button is in the same position in the top left. Simply move your cursor to view either of them.

<img src="{{ site.baseurl }}/images/documentation/video-fullscreen.png" />

Vocal uses smart maximizing to go fullscreen. If you are not playing video the maximize button will maximize the app, but if you are playing video the maximize button will automatically take you fullscreen.

# Preferences

There are a number of preferences that you can set inside the app:

<div class="float-left clear half"><img src="{{ site.baseurl }}/images/documentation/preferences.png" /></div>

* Whether or not you want to automatically download new episodes when they are discovered.
* Whether or not to automatically delete played files that are more than one week old.
* The number of seconds to skip forward and backward when skipping.

---

# Keyboard Shortcuts and Media Keys

Vocal supports the media keys found on most keyboards. It also has several keyboard shortcuts defined:

* *Control* + *P or Space* : Play/Pause
* *Left/Right* : Skip backward/forward
* *F* or *F11* : Go fullscreen
* *Control + Q* : Quit

# Sound Menu Support

<div class="float-right clear half"><img src="{{ site.baseurl }}/images/documentation/sound-menu.png" /></div>

Vocal supports the MPRIS2 specification, which means playback can be controlled by the sound menus in elementary OS and most other desktops.

---

# FAQ

##Q: How do I reset Vocal?

A: Delete `~/.config/vocal` and `~/.local/share/vocal`, either with a file browser or by entering the following command into Terminal:

`rm -rf ~/.config/vocal && rm -rf ~/.local/share/vocal`

##Q: Why isn't the 'All Podcasts/Video/Audio' switcher showing up for me like in the screenshots?

A: The switcher automatically appears whenever you add your first video podcast.