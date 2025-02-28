# alternative-front-ends-abridged
_All credit to [@mendel5's original alternative-front-ends](https://github.com/mendel5/alternative-front-ends)._

**WIP (work-in-progress)**

Overview of alternative open source front-ends for popular internet platforms (e.g. YouTube, Twitter, etc.).

I have found [@mendel5](https://github.com/mendel5)'s *alternative-front-ends* repo to be incredibly useful both as a source of inspiration for what i may want to self-host on my home server and as a resource for how to attain a **faster** and **more secure** way of navigating the internet. However i have found that many of the projects listed are either no longer maintained, no longer functional, or far below my standard of trust, given my general code literacy and ability to audit the code. This will be primarily a distillation of that original list, and if i come across new ones i choose to incorporate they will obviously be included. 

My choice of organization might be a bit different as well. 

## Contents
### Social Media
- [YouTube](#youtube)
- [YouTube Music](#youtube-music)
- [Twitter](#twitter)
- [Reddit](#reddit)
- [TikTok](#tiktok)
- [Facebook](#facebook)
- [Facebook Messenger](#facebook-messenger)
- [Mastodon](#mastodon)
### Services
#### De-Google
- [Google Search](#google-search)
- [Google Translate](#google-translate)
#### Hosting
- [Imgur](#imgur)
#### Streaming
- [Twitch](#twitch)
#### Chat
- [Discord](#discord)
- [Telegram](#telegram)
#### Music
- [Spotify](#spotify)
- [Apple Music](#apple-music)
- [Bandcamp](#bandcamp)
- [Shazam](#shazam)
- [Medium](#medium)
#### Misc
- [IMDb](#imdb)
- [Quora](#quora)
- [Reuters](#reuters)
- [Hacker News](#hacker-news)
#### Compatibility
- [Apple AirPlay](#apple-airplay)

- [Other services](#other-services)
- [Redirection](#redirection)
- [Related projects](#related-projects)
- [About this repository](#about-this-repository)



## Overview

### Social Media
#### Youtube

- [Invidious](https://github.com/iv-org/invidious): Invidious is an alternative front-end to YouTube - Lightweight, no ads, no tracking, no JavaScript required
  - Home page: https://invidious.io
  - Invidious instances: https://docs.invidious.io/instances/
  - Invidious instances API: https://api.invidious.io
  - Installation guide for self-hosting: https://docs.invidious.io/installation/

- [Piped](https://github.com/TeamPiped/Piped): An alternative privacy-friendly YouTube frontend which is efficient by design - Lightweight, no ads, no tracking
  - Official instance: https://piped.video
  - Public instances: https://github.com/TeamPiped/Piped/wiki/Instances
  - Installation guide for self-hosting: https://github.com/TeamPiped/Documentation/blob/main/content/docs/self-hosting/index.md

- [CloudTube](https://git.sr.ht/~cadence/cloudtube): Alternative front-end for Invidious
  - Official instance: https://tube.cadence.moe
  - Installation guide for self-hosting: https://git.sr.ht/~cadence/tube-docs/tree/main/item/docs/cloudtube/Installing%20CloudTube.md

- [YouTube.js](https://github.com/LuanRT/YouTube.js): Full-featured wrapper around the Innertube API, which is what YouTube itself uses

- [FreeTube](https://github.com/FreeTubeApp/FreeTube): Open source YouTube desktop player for privacy on Windows, Mac and Linux
  - Official Instance: https://freetubeapp.io/

- [Youtube-viewer](https://github.com/trizen/youtube-viewer): Lightweight YouTube client for Linux

- [pipe-viewer](https://github.com/trizen/pipe-viewer): A lightweight application (fork of straw-viewer) for searching and playing videos from YouTube.

- [NewPipe](https://github.com/TeamNewPipe/NewPipe): A libre lightweight streaming front-end for Android

- [Youtube-dl](https://github.com/ytdl-org/youtube-dl): Command-line program to download videos from YouTube.com and other video sites

- [OpenVideoDownloader aka jely2002/youtube-dl-gui](https://github.com/jely2002/youtube-dl-gui): A cross-platform GUI for youtube-dl made in Electron and node.js

- [Vividl](https://github.com/Bluegrams/Vividl): Modern Windows GUI for youtube-dl

- [Tartube](https://github.com/axcore/tartube): A GUI front-end for youtube-dl, partly based on youtube-dl-gui and written in Python 3 / Gtk 3

- [ytmdl](https://github.com/deepjyoti30/ytmdl): A simple app to get songs from YouTube in mp3 format with artist name, album name etc from sources like iTunes, LastFM, Deezer, Gaana etc.

- [ViewTube](https://github.com/ViewTube/viewtube-vue): An alternative front-end for YouTube, written in Vue.js, uses Plyr video player; supports SponsorBlock, multiple Invidious instances support, chapters

- [youtube-local](https://github.com/user234683/youtube-local): Browser-based client for watching Youtube anonymously and with greater page performance

- [yt-local](https://git.sr.ht/~heckyel/yt-local): Browser-based client for watching Youtube anonymously without forcing javascript (Fork of [youtube-local](https://github.com/user234683/youtube-local))

- [SkyTube](https://github.com/SkyTubeTeam/SkyTube): An open-source YouTube app for Android

- [yt-dlp](https://github.com/yt-dlp/yt-dlp): A youtube-dl fork with additional features and fixes

- [uYouPlus](https://github.com/qnblackcat/uYouPlus): uYouPlus (uYou+) is an alternative YouTube app for Apple's iOS and iPadOS

- [SmartTubeNext](https://github.com/yuliskov/SmartTubeNext): SmartTubeNext is an advanced YouTube app for Android TVs and TV boxes, free and open source. It is not a live TV client and does not support "YouTube TV"

- [TubeSync](https://github.com/meeb/tubesync): TubeSync is a PVR (personal video recorder) for YouTube. It syncs YouTube channels and playlists to a locally hosted media server

- [TubeArchivist](https://github.com/tubearchivist/tubearchivist): A self hosted YouTube media server

- [mps-youtube](https://github.com/mps-youtube/mps-youtube): Terminal based YouTube player and downloader

- [yattee](https://github.com/yattee/yattee): Alternative YouTube frontend for iOS, tvOS and macOS built with Invidious and Piped, supports sponsorblock

- [LibreTube](https://github.com/libre-tube/LibreTube): Android frontend for YouTube, based on Piped

### YouTube Music

- [ytmdesktop](https://github.com/ytmdesktop/ytmdesktop): Cross-platform (Windows, Mac, and Linux) desktop app for YouTube Music. Has a (proprietary?) remote control app for Android

- [AudioTube](https://invent.kde.org/plasma-mobile/audiotube): Client for YouTube Music. Plasma-mobile project with an interface designed for Linux phones

- [th-ch/youtube-music](https://github.com/th-ch/youtube-music): YouTube Music desktop app based on Electron bundled with custom plugins (including built-in ad blocker and downloader)

### Twitter

- [Nitter](https://github.com/zedeus/nitter): Alternative Twitter front-end - Lightweight, no ads, no tracking, no JavaScript required
  - Official instance: [nitter.net](https://nitter.net)
  - Public instances: https://github.com/zedeus/nitter/wiki/Instances
  - Example: Troy Hunt on [Twitter](https://twitter.com/troyhunt) and [Nitter](https://nitter.net/troyhunt)

- [Tweepy](https://github.com/tweepy/tweepy): Twitter for Python

### Reddit

- [Libreddit](https://github.com/libreddit/libreddit): Alternative front-end for Reddit. Themed around Reddit's new design - Lightweight, no JavaScript, no ads, no tracking
  - Public instances: https://github.com/libreddit/libreddit-instances/blob/master/instances.md

- [Eddrit](https://github.com/corenting/eddrit): Alternative front-end for Reddit, inspired by Nitter, built with Python & Starlette

- [Top of Reddit](https://github.com/mgerb/top-of-reddit): Top Reddit posts every day

- [Infinity](https://github.com/Docile-Alligator/Infinity-For-Reddit): Reddit client for Android
  - Available on [F-Droid](https://f-droid.org/en/packages/ml.docilealligator.infinityforreddit)
  
- [kddit](https://git.kalli.st/kallist/kddit-spaghetti): uWSGI frontend for Reddit.com written in Python
  - Official instance: https://kddit.kalli.st

- [Troddit](https://github.com/burhan-syed/troddit): A web client for Reddit
  - Official instance: https://www.troddit.com

### TikTok

- [ProxiTok](https://github.com/pablouser1/ProxiTok): Open source alternative frontend for TikTok made with PHP
  - Official instance: https://proxitok.pabloferreiro.es/

### Imgur

- [Rimgo](https://codeberg.org/video-prize-ranch/rimgo): Self-hosted frontend for Imgur ritten in Go
  - Public instances: https://codeberg.org/video-prize-ranch/rimgo#instances

### Spotify

- [psst](https://github.com/jpochyla/psst): Fast and multi-platform Spotify client with native GUI

- [spot](https://github.com/xou816/spot): Gtk/Rust native Spotify client for the GNOME desktop. Only works with premium accounts

- [spotube](https://github.com/KRTirtho/spotube): A lightweight and free Spotify crossplatform-client which handles playback manually, streams music using Youtube & no Spotify premium account is needed

- [SpotX](https://github.com/amd64fox/SpotX): Modified Spotify Client for Windows (Windows Only) - Blocking ads and updates for the desktop version of Spotify, disabling podcasts and more

- [librespot](https://github.com/librespot-org/librespot): Requires Spotify Premium Account - librespot is an open source client library for Spotify. It enables applications to use Spotify's service to control and play music via various backends, and to act as a Spotify Connect receiver. It is an alternative to the official and now deprecated closed-source libspotify. Additionally, it will provide extra features which are not available in the official library

- [spotifyd](https://github.com/Spotifyd/spotifyd): unix daemon, using librespot.

### Apple Music [NOT MAINTAINED]

- [Cider](https://github.com/ciderapp/Cider): Cross-platform Apple Music experience based on Electron and Vue.js written from scratch with performance in mind

### Bandcamp [NOT MAINTAINED]

- [Tent](https://codeberg.org/sun/Tent): A simple alternative front-end for Bandcamp that does not require JavaScript and proxies all requests

### Twitch

- [streamlink-twitch-gui](https://github.com/streamlink/streamlink-twitch-gui): Multi platform Twitch.tv browser for Streamlink

- [Twire](https://github.com/twireapp/Twire): Alternative and open source Twitch client for Android

- [Xtra](https://github.com/crackededed/Xtra): Twitch player and browser for Android

### Discord

- [gtkcord4](https://github.com/diamondburned/gtkcord4): A lightweight Discord client written in Golang which uses GTK3 for the user interface

- [openasar](https://github.com/GooseMod/OpenAsar): An open-source alternative of Discord desktop's app.asar

### Google Search

- [Whoogle Search](https://github.com/benbusby/whoogle-search): A self-hosted, ad-free, privacy-respecting metasearch engine for Google
  - Public instances: https://github.com/benbusby/whoogle-search#public-instances

- [SearXNG](https://github.com/searxng/searxng): SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled (SearXNG is a fork of searx)


### Google Translate

- [DeepL Android](https://github.com/sakusaku3939/DeepLAndroid): Unofficial Android client for DeepL
  - Available on [F-Droid](https://f-droid.org/en/packages/com.example.deeplviewer)

### Facebook

- [SlimSocial](https://github.com/rignaneseleo/SlimSocial-for-Facebook): Android, alternative front-end for Facebook, built with Java

### Facebook Messenger

- [Caprine](https://github.com/sindresorhus/caprine): Unofficial and privacy-focused Facebook Messenger app with many useful features

### Mastodon

- [Sengi](https://github.com/NicolasConstant/sengi): cross-platform multi-account Mastodon & Pleroma desktop client

- [Tusky](https://github.com/tuskyapp/Tusky): lightweight Android Mastodon client

- [Fedilab](https://codeberg.org/tom79/Fedilab): multi-account Android Mastodon client

### Medium

- [Scribe](https://sr.ht/~edwardloveall/Scribe): Alternative front-end to Medium.com
  - Official website: https://scribe.rip

### IMDb

- [libremdb](https://github.com/zyachel/libremdb): A FOSS alternative front-end to IMDb.
  - Official instance: https://libremdb.iket.me/
  - Public Instances: https://github.com/zyachel/libremdb#instances

### Quora

- [Quetre](https://github.com/zyachel/quetre): A libre front-end for Quora
  - Official website: https://quetre.iket.me/
  - Public instances: https://github.com/zyachel/quetre#instances

### Reuters

- [Neuters](https://github.com/HookedBehemoth/neuters): An alternative front-end to Reuters.com. It is intented to be lightweight and fast, and was heavily inspired by Nitter
  - Official instance: https://neuters.de

### Apple AirPlay

- [RPiPlay](https://github.com/FD-/RPiPlay): An open-source AirPlay mirroring server for the Raspberry Pi. Supports iOS 9 and up.

- [air-pi-play](https://github.com/rahul-thakoor/air-pi-play): Turn a Raspberry Pi into an Airplay server using RPiPlay to enable screen mirroring on tvs, monitors and projectors.

### Shazam

- [SongRec](https://github.com/marin-m/SongRec): Open-source Shazam client for Linux, written in Rust

### Telegram

- [Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS): Unofficial, FOSS-friendly fork of the original Telegram client for Android

### Other services

- [PrivateBin](https://github.com/PrivateBin/PrivateBin): Zero knowledge encrypted paste-bin. A minimalist, open source online pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256 bits AES

- [snapdrop](https://github.com/RobinLinus/snapdrop): Similar to Apple's Airdrop but in your browser. A Progressive Web App for local file sharing

- [hedgedoc](https://github.com/hedgedoc/hedgedoc): Collaborative markdown editor. A platform to write and share markdown

- [etherpad-lite](https://github.com/ether/etherpad-lite): Collaborative rich text editor. A modern really-real-time collaborative document editor

- [ArchiveBox](https://github.com/ArchiveBox/ArchiveBox): Open source self-hosted web archiving. Takes URLs/browser history/bookmarks/Pocket/Pinboard/etc., saves HTML, JS, PDFs, media, and more

- [Wikiless](https://github.com/Metastem/wikiless): A free open source alternative Wikipedia front-end focused on privacy
  - Official instance: https://wikiless.org/
  - Public instances: https://github.com/Metastem/wikiless


## Redirection

- [Privacy Redirect](https://github.com/SimonBrazell/privacy-redirect): A simple web extension that redirects Twitter, YouTube, & Google Maps requests to privacy friendly alternatives
  - [Firefox Add-On: Privacy Redirect](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect)
  - [Chrome Extension: Privacy Redirect](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb)

- [libredirect](https://github.com/libredirect/libredirect): A web extension that redirects popular sites to alternative privacy-friendly frontends and backends. Actively maintained fork of Privacy Redirect that supports Youtube, Youtube Music, Twitter, TikTok, Imgur, Reddit, Searx, Google Translate, Google Maps, Wikipedia, and Medium
  - [Firefox Add-On](https://addons.mozilla.org/firefox/addon/libredirect/)
  - [Chrome Extension](https://libredirect.github.io/download_chromium.html)

- [Farside](https://github.com/benbusby/farside): Farside provides links that automatically redirect to working instances of privacy-oriented alternative frontends, such as Nitter, Libreddit, etc. This allows for users to have more reliable access to the available public instances for a particular service, while also helping to distribute traffic more evenly across all instances and avoid performance bottlenecks and rate-limiting.

- [UntrackMe](https://framagit.org/tom79/nitterizeme): UntrackMe transforms Twitter, YouTube, Reddit and Medium and Wikipedia links to links of open source, privacy friendly front-ends. Converts Google Maps links to OpenStreetMap links. Removes tracking parameters from any url. Then delegates the action to other apps that are capable of handling them. (Android app)

- [Redirector](https://github.com/einaregilsson/Redirector): Web browser extension (Firefox, Vivaldi, Chrome, Opera, Edge) to redirect URLs based on regex or wildcard patterns.
  - [Firefox Add-On: Redirector](https://addons.mozilla.org/firefox/addon/redirector/)
  - [Chrome Extension: Redirector](https://chrome.google.com/webstore/detail/redirector/ocgpenflpmgnfapjedencafcfakcekcd)

## Related projects

- [StreetComplete](https://github.com/streetcomplete/StreetComplete): Easy to use OpenStreetMap editor for Android

- [Matrix.org's Synapse](https://github.com/matrix-org/synapse): End-to-end-encrypted messaging. Matrix reference homeserver. See also [matrix.org](https://matrix.org).

- [Pluja's Awesome Privacy](https://github.com/pluja/awesome-privacy): A curated list of services and alternatives that respect your privacy because privacy matters.

- [12ft.io / 12ft Ladder](https://12ft.io): 12ft Ladder is a free service for reading news articles. Prepend 12ft.io/ to the URL of any paywalled page, and we'll try our best to remove the paywall and get you access to the article. It is similar to Outline.com which is not available anymore.
  - Note: The source code of 12ft Ladder is not available under a free/open-source license.

- [Youtube Vanced](https://github.com/YTVanced): Youtube replacement app for the Android platform: YouTube Vanced is the stock Android YouTube app, but better. It includes adblocking, true amoled dark mode and a lot more. Use the Vanced Manager to install YouTube Vanced with ease.
  - Official website with install instructions: https://vancedapp.com
  - Note: The source code of Youtube Vanced is not available under a free/open-source license.
  - For an explanation about the origin of Youtube Vanced see here: https://old.reddit.com/r/Vanced/comments/o3xm9m/if_youtube_vanced_isnt_open_source_and_doesnt/h2ec7wf/
  - Vanced was forced to shut down by Google due to legal reasons. The project https://github.com/revanced tries to continue its legacy

## About this repository

This overview originally included three alternative front-ends: Invidious (for YouTube), Bibliogram (for Instagram) and Nitter (for Twitter). Therefore it was named `alternative front-ends`. As more projects have been added to the repository, the listed projects partially left the scope of *alternative front-ends*.

For example, `youtube-dl` is not a front-end, but can be generally described as an open source project that interacts with the internet platform Youtube.

Therefore the name `alternative front-ends` does not capture the full scope of the listed projects anymore. Maybe this repository will be renamed in the future to better reflect the larger scope. A possible name might be `open-source-alternatives` or something similar.
