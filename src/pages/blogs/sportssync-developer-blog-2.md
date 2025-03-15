---
layout: ../../layouts/Blog Post Layout.astro
pageTitle: "Sportssync Developer Blog #2"
title: "Sportssync Developer Blog #2"
pubDate: "2025-03-14"
readingTime: 6 Min
---

## Introduction

Since the last blog update, I've made some major improvements to the extension. New highly requested features have been added, a complete rework of the code base, an updated roadmap with new planned features, and more. The different game views unfortunately will not be ready for this update, but I've begun work and included some sneak peaks below! I've been hard at work bringing new features to this extension and I'm excited for everyone to try them out soon!

## The Highlights

Live Scores Menubar Command: Created a new menu bar command to view live scores, final scores, and game schedule directly from the menu bar. Clicking on games will set them as the menubar title, and a refresh option is available to remove the game (this can also be done by clicking on a different game). This will then stay as the title, and will reflect game updates every 15 seconds. It will support every league. However, only your favorite league will be displayed (the one selected in the settings panel).

Favorite Team Dashboard Command: Created a new favorite team command to view scheduled games, completed games, live scores, team information, team standings information, injuries, transactions and articles. This will all be found in a single command with 3 dropdowns (completed games, scheduled games, tracker). It will support a single team, and must be configured through the settings.

Tracker Command: This will be replacing most news commands (except f1 and soccer). It will provide three dropdowns to view news articles, injuries, and transactions for each league (college leagues are excluded from injuries and transactions).

### Quality of Life Upgrades:

- Dropdown selections now save, and commands will re open to them when relaunched. However this is on a global basis not per command (therefore if you select the second dropdown, that is saved globally). I'm planning to fix this in the next update, although no guarantees.
- Added country icons to F1 Races
- Added a "Category" tooltip to the new tags
- Added a "Race #" tooltip to the F1 Race Count Tag
- Added a global refresh action to refresh the api data, without closing a command
- Added a new copy link action to article views
- Updated the news view to now show the last 50 articles (except for soccer which will show 20)

### Bug Fixes:

- Fixed an issue causing a winner to be displayed in the F1 Races and Schedule Command when Qualifying laps have been completed, but races haven't. It will now display a winner once the race has been completed.
- Added fallbacks to all commands

### Other Updates:

- New preferences in the settings (required for favorite team dashboard and live scores menubar)
- New refreshed icon with new colors
- Created a new empty view that displays when data is not found
- Updated search bar placeholders to accurately reflect the context of the command
- Updated action titles to be context aware (example: instead of saying team details, or away team details, it will now say View "Toronto Maple Leafs" Details)
- Combined basketball scores and schedule with college basketball scores and schedule.
- Added NCAA M and W articles to the basketball tracker command.
- Changed College Basketball to now use the more preferred "NCAA M" and "NCAA W" naming scheme instead of "MNCAA" and "WNCAA"
- Removed the date accessory from articles. Articles will now be displayed in different sections, with the date as the title (just like in scores and schedule)
- README Roadmap will now reflect the newest updates and has new planned features
- README has some additional info about preferences, disclaimer, and data source
- Added new screenshots based showing off the newest update
- Changed icon in news view from calendar to megaphone

<a href="https://github.com/daniyalmaster693/sportssync/blob/main/CHANGELOG.md" aria-label="Sportssync Raycast Store Page" target="_blank">View Full Changelog Here</a>

## Updated Feature Previews:

- New Preferences Settings

<img src="/Sportssync Commands.webp" alt="Preference Panel Configuration">

- Favorite Team Dashboard Tracker Preview

<img src="/Sportssync-3.webp" alt="Favorite Team Dashboard Preview">

- Live Scores Menubar Preview

<img src="/Sportssync-4.webp" alt="Live Scores Menubar Command Preview">

- Tracker Injuries View Preview

<img src="/Sportssync-6.webp" alt="Tracker Injuries Preview">

- Tracker Articles View Preview

<img src="/Sportssync-5.webp" alt="Tracker News View">

- Tracker Transactions Preview

<img src="/Sportssync-7.webp" alt="Tracker Transactions View">

- Scores and Schedule Command with new and context aware actions

<img src="/Sportssync Actions.webp" alt="Updated Context Aware Actions">

## Updated Roadmap:

- ~~Live Scores Command (Menubar): View live scores and upcoming games, and click on games to set them as the menu bar title, allowing users to view scores with automatic refreshes.~~
- ~~Tracker Command: A command to view injuries and transactions~~
- ~~Past Scores Command: A separate command (or something integrated into the scores and schedules command) to allow users to view scores for previous games (up to a few days)~~
- ~~Favorite Team Command: A single command to follow a specific team~~
- Roster View for Standings Command
- Player Profiles from Roster View
- Universal Player Search Command
- Article Viewer for Tracker Command (Read Articles directly in Raycast)
- Add to Calendar Action for games
- Current Leagues Planned: (UFC, Boxing, WWE, Nascar)
- Additional Leagues: Please request any leagues that you'd like me to add support for, and I'll look into seeing what I can do.

**_In depth stats, for the scores and schedule command_**

- Play by Play Tracker: A menu to view play by play events during live games
- Team Stats and Team Matchups: A separate similar to the play by play tracker, to view individual team stats, leaders, and the season series for upcoming games
- Final Team Stats: Another separate menu to view the final team stats after a game has been completed, including team leaders, player stats, and overall team stats

## Conclusion

Once again thank you all for the support! Once this update is released, I will continue work on adding different game views (pre game matchups, play by play events, final game stats, new articles directly in raycast, roster views, player profiles), and some additional smaller quality of life upgrades. Stay Tuned :)
