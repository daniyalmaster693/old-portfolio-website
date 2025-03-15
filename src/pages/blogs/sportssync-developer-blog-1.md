---
layout: ../../layouts/Blog Post Layout.astro
pageTitle: "Sportssync Developer Blog #1"
title: "Sportssync Developer Blog #1"
pubDate: "2025-03-04"
readingTime: 6 Min
---

<img src="/Sportssync Installs.webp" alt="Sportssync Installs">

## Introduction

First off, thank you all for 250 installs! It's crazy how much support has been shown for this extension since the original version launched and the original post. I've since released a small update, and have a bigger update currently being reviewed (should be approved in the next few days). I've been hard at work, adding new features and improving each command. I'm currently pretty satisfied with the current state of each base command, and am looking forward to adding some new commands and views. Although I will continue to add some new features and improvements with each update.

## The Highlights:

Past Scores Feature: In the scores and schedule commands, I've updated each command to now show the final scores for the past 3 days, the games for the current day, and the games for the next 5 days. It integrates nicely with the existing functionality, and is support in every league. And specifically for the F1 Results and Schedule Command I've set it to instead show the entire schedule for the entire year, so you can see every race for the season.

Visual upgrades: new icons that dynamically update in the scores and schedule commands, race number indicators in the f1 results and schedule command, position indicators in the standings commands, headline category indicators for the news commands. In addition, tooltips have been added for all new icons and indicators (for increased accessibility)

MLB Improvements: Now that the season has started (at least spring training) I got a chance to take a look at the api properly, and update and fix some issues. First the standings should display correctly now. Live games will show a detail instead of time remaining (for ex: bottom of 9th).

F1 Improvements: Race titles will now shore more detail, and subtitles have been added for the location of each race

Live Score Menu Bar Command: Not quite ready yet, so will not be shipped in this update. Although I have made some good progress, hopefully will be ready for the next update which will also have the favorite teams feature, and some other improvements.

New League: Champions League (Soccer)

## Updated Screenshots:

- View of live scores and upcoming games in the NHL Scores and Schedule Command with new icons:

<img src="/Updated Scores and Schedule Command.webp" alt="Updated Scores and Schedule Command">

- Past Scores in the NHL Scores and Schedule Command and New Checkmark Icons:

<img src="/Past Scores Feature.webp" alt="Sportssync Past Scores Feature">

- View of the improved NBA Standings Command with new Position indicators:

<img src="/Updated Standings.webp" alt="Sportssync Past Scores Feature">

- Headline Category Indicators for the F1 News Command, and New Calendar Icons:

<img src="/Updated News.webp" alt="Sportssync Past Scores Feature">

- Preview of the upcoming live scores menu bar command:

<video controls autoplay>
  <source src="https://i.imgur.com/wmWQFUM.mp4" type="video/mp4">
</video>

## Feedback and Upcoming Updates

I've taken your feedback from the last post and I will be adding a favorites feature in the next update, with the live scores command. Please leave any suggestions in the github repo, and I'll do my best to respond and hopefully implement them. Note: There is already a roadmap at the bottom of the README in the repo.

## Full change log:

- Added a new league: Champions League
- Fixed an issue causing the record in nhl standings command to show up as undefined
- Added pts as a stat in the nhl standings command
- Fixed an issue causing an error when links are not available
- Updated the F1 Scores and Schedule command title: F1 Results and Schedule
- Added proper support for 4 Nations for the NHL Scores and Schedule Command
- Updated the NHL Standings command to use divisions instead of conferences
- Updated each scores and schedule command to now show the scores for the past 3 days, and the games for the next 5 days
- Fixed an MLB Standings Bug causing the data to fail to display when there have been 0 GP
  Changed the MLB Scores and Schedule command to now show a short detail instead of the display clock (for more relevant information)
- Added checkmark, calendar, and x mark icons to the scores and schedule commands that change based on the game state
- Added a calendar icon to the news commands
- Added a new tag to the news commands for the article type
- Added a new starting soon indicator to the scores and schedule commands. It will display a hazard icon, and will display the game time in yellow, when a game is going to start in the next 30 minutes
- Changed the F1 Results and Schedule command to show the schedule for the entire year
- Added a tag in the F1 Results and Schedule command to show the race number
- Changed the titles in the F1 Results and Schedule command to include more detail
- Added a subtitle to the F1 Results and Schedule command to show the city and country for each race
- Added a new tag in the standings commands to show whether a team is in the playoffs, or their current position in the league (varies based on the league). Includes different colors and icons that update dynamically
- Fixed a bug in the MLB Standings command causing incorrect data to display
- Added a "scheduled" tooltip for scheduled games

## Conclusion

Once again thank you all for the support! Once this update is released, I will begin work on adding major features such as different game views (pre game matchups, play by play events, final game stats), the live scores menu bar command, a favorite team feature and more. Stay tuned :)
