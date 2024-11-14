# EefFox

## Table of Contents

<!-- mtoc-start -->

* [Intro](#intro)
* [FirefoxCSS Setup](#firefoxcss-setup)
* [Extensions](#extensions)
  * [Must Haves](#must-haves)
    * [Bitwarden Password Manager (or equivalent)](#bitwarden-password-manager-or-equivalent)
    * [Close Window Button](#close-window-button)
    * [Dark Reader (or equivalent)](#dark-reader-or-equivalent)
    * [Facebook Container](#facebook-container)
    * [Firefox Color](#firefox-color)
    * [Firefox Multi-Account Containers](#firefox-multi-account-containers)
    * [Gesturefy](#gesturefy)
    * [Minimize Window Button](#minimize-window-button)
    * [Movable window-maximize-button](#movable-window-maximize-button)
    * [Privacy Badger](#privacy-badger)
    * [Sidebery](#sidebery)
    * [uBlock Origin](#ublock-origin)
  * [Recommended](#recommended)
    * [Keepa - Amazon Price Tracker](#keepa---amazon-price-tracker)
    * [React Developer Tools](#react-developer-tools)
    * [Return YouTube Dislike](#return-youtube-dislike)
    * [Search by Image](#search-by-image)
    * [SponsorBlock for YouTube - Skip Sponsorships](#sponsorblock-for-youtube---skip-sponsorships)
    * [Tabliss](#tabliss)
    * [WindowSizer](#windowsizer)
  * [Neat](#neat)
    * [Flagfox](#flagfox)
    * [YouTube High Definition](#youtube-high-definition)
* [Sidebery Setup](#sidebery-setup)
* [Firefox Colors](#firefox-colors)
* [Toolbar](#toolbar)

<!-- mtoc-end -->

## Intro

My Firefox setup
Intended to look similar to Arc

## FirefoxCSS Setup

[Here](https://mrotherguy.github.io/ToyfoCSS/) is a good, thorough FirefoxCSS tutorial.
[Here](https://www.userchrome.org/) is another good resource. For a quick start,
follow these steps:

- Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in `about:config`
- Go to `about:support` and open the folder for your profile.
- Copy [my CSS](userChrome.css) into this folder or clone this repo into it.
  (or make your own)
- Make sure you restart Firefox afterwards for it to apply.

## Extensions

### Must Haves

#### Bitwarden Password Manager (or equivalent)

I use Bitwarden to manage my passwords. It's open source, free, and
has software for all platforms.

#### Close Window Button

A button in your toolbar to close the current window.
Must have as I hide the title bar.

#### Dark Reader (or equivalent)

Enables dark mode on all websites. This is a must-have for me.

#### Facebook Container

Contains all Facebook activity to prevent tracking which Facebook
loves to do.

#### Firefox Color

Customize the browser's colors to your liking.

#### Firefox Multi-Account Containers

Helps manage multiple accounts on the same site.

#### Gesturefy

I love mouse gestures. This is a must-have.

#### Minimize Window Button

Similar to [Close Window Button](#close-window-button), but for minimizing.

#### Movable window-maximize-button

Similar to [Close Window Button](#close-window-button), but for maximizing.

#### Privacy Badger

For internet privacy. Blocks trackers.

#### Sidebery

Great vertical tab extension. I love it for containers and sub-tabs.

#### uBlock Origin

Ad blocker.

### Recommended

#### Keepa - Amazon Price Tracker

Shows the price history of Amazon products.

#### React Developer Tools

For React development.

#### Return YouTube Dislike

Shows the dislike count on YouTube.

#### Search by Image

Easily reverse image search any image across the web.

#### SponsorBlock for YouTube - Skip Sponsorships

Skip sponsored segments of YouTube videos.

#### Tabliss

Great, customizable new tab page.

#### WindowSizer

Lets you resize the window to a specific size.

### Neat

#### Flagfox

Shows the country of the current website's server.

#### YouTube High Definition

Automatically plays YouTube videos in the highest quality.

## Sidebery Setup

[Sidebery](#sidebery) is a great vertical tab extension. You can import my settings
from [here](Sidebery/sidebery-data.json) by going to `Sidebery > Settings >
Help > Import addon data`. I also added just my styles [here](Sidebery/sidebery-data_justStyles.json).
Adding just styles will not change your settings and is likely better so it doesn't
affect your containers.

The important things to me are:

- Having at least the following containers (can be done in Sidebery or
  [Multi-Account Containers](#firefox-multi-account-containers) or Firefox Settings):

  - Personal
  - Work
  - Work 2 (for secondary work accounts)

- Having a panel for each container (`Sidebery > Settings > Navigation Bar`) with
  these settings:
  - Container of new tab: (relevant container)
  - Reopen tab that was dropped to this panel in container: (relevant container)

## Firefox Colors

I have exported my colors [here](<Firefox Colors/theme.zip>). To automatically import
them, I need to do some other things. I will update this when I figure it out.

You can unzip it and look at the `manifest.json` for the color values.

## Toolbar

![image](https://github.com/user-attachments/assets/60a29190-0783-468a-9f78-bfc23f3f8eb8)
Here is how I have my toolbar customized. The minimize, open, and close buttons on the right
are from extensions mentioned above. I belive they can be done using CSS but I haven't tried.
