Podnapisi.NET KODI add-on
=============================
Search and download subtitles for movies and TV-Series from Podnapisi.NET
                            
Changelog

5.5.0
- ported to python3 for matrix (by corinzio)

5.4.2
- fix: Unicode issue with languages
- fix: Year was inside the title, it must be removed
- fix: Used year of the episode, switched to Premiered info
- fix: Podnapisi.NET does not have Serbo-Croatian language, it resulted into None and crashed the addon
- Removed/disabled old XML-RPC based API
- Removed login credentials (will probably be readded later)
- Added search with IMDb number, where possible
- all changes in 5.4.2 by MasterMind2k

5.4.0
- use new API for better search and easier download.

5.3.0
- add more exact hash algorithms for more precise search. Hash search/match needs to be enabled in settings

5.2.0
- restructure search, use only web to search as SSP is way to slow.
- [fix] xbmcvfs might return false if no slash is at the end of folder

5.1.1
- fix cp/monster
- upload hash only for local content
- check for hash results first, avoids script error

5.1.0
- many cleanups
- added option(default false) to upload hash match for the chosen subtitle. It helps service provider to build database of exact hash matches(syncs).

5.0.8
- cleanup logging
- simplify search for multiple languages, its possible to send all 3 languages in one search query

5.0.7
- cleanup, notify if login fails

5.0.6
- add new extract method, should take care of accented characters

5.0.5
- cosmetics
- Fix unzip issues with non-ascii in ziplib library

5.0.4
- add notification that we dont support manual search 

5.0.3
- clean temp dir and use python zipfile for extraction

5.0.2
- fix missing languages

5.0.1
- icon.png and added logo.png for skin to use in window

5.0.0
- move the service out of XBMC Subtitles
