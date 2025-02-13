---
layout: ../../layouts/Project Page Layout.astro
pageTitle: "Sportssync | Daniyal Master"
title: "Sportssync Raycast Extension"
description: "View sports scores, news, and standings in Raycast"
date: "Feb 13th"
creator: "Daniyal Master"
order: "0"
---

<img src="/sportssync 2025-01-12 at 18.05.40.webp" alt="Sportssync Screenshot">

## Overview

Sportssync is a raycast extension that keeps you updated with live scores, standings, and news across. With dynamic updates, you can stay in the loop without interrupting your workflow.

## Goals and Motivation

The goal of Raycast has always been to create seamless workflows that eliminate the friction between tasks, allowing users to stay focused. A sports extension has been long requested, something to provide an easy way to stay up to date with scores, news, standings, and relevant information across many sports through just the Raycast search bar.

Sportssync delivers this solution, bridging the gap between sports and productivity. Using the ESPN Sports API, I built an extension that would deliver easy access to live scores, standings, and news, all without interrupting your work.

## Commands

- **Scores and Schedule:** Dynamically view live scores, game times, and completed scores (updates dynamically based on the game state)
- **Standings Command:** View team standings and in-depth stats (differs based on the league)
- **News Command:** View news articles and headlines

## Supported Leagues

_Leagues that are fully supported feature the following: a scores and schedule, standings, and news command_

- NHL (Fully supported)
- NBA (Fully Supported)
- WNBA (Fully supported)
- Men's College Basketball (Only scores and news)
- Women's College Basketball (Only scores and news)
- NFL (Fully supported)
- College Football (Men's) - (Only scores and news)
- MLB (Fully supported)
- F1 (Fully supported)
- EPL (English Premier League) - (Fully supported)
- SLL (LALIGA) - (Fully supported)
- GER (German Bundesliga) - (Fully supported)
- ITA (Italian Serie A) - (Fully supported)

## Roadmap

- **Live Scores Command (Menubar):** View live scores and upcoming games, and click on games to set them as the menu bar title, allowing users to view scores with automatic refreshes.
- **Stats command:** A command to view player stats.
- **Tracker Command:** A command to view injuries and transactions.
- **Past Scores Command:** A separate command (or something integrated into the scores and schedules command) to allow users to view scores for previous games (up to a few days).
- **Additional Leagues:** Please request any leagues that you'd like me to add support for, and I'll look into seeing what I can do.

_In-depth stats, for the scores and schedule command:_

- Play by Play Tracker: A menu to view play-by-play events during live games.
- Team Stats and Team Matchups: A separate menu similar to the play-by-play tracker, to view individual team stats, leaders, and the season series for upcoming games.
- Final Team Stats: Another separate menu to view the final team stats after a game has been completed, including team leaders, player stats, and overall team stats.

## Links

- <a href="https://github.com/daniyalmaster693/sportssync" aria-label="Sportssync Github Repository" target="_blank">Github Repository</a>
- <a href="https://www.raycast.com/daniyal_master/sportssync" aria-label="Sportssync Raycast Store Page" target="_blank">Raycast Store</a>

## Tech Stack Used

- Typescript
- React
- Raycast API

## Challenges and Solutions

Due to the nature of this project (being open source, and non profit), I couldn't justify paying for a sports API. I decided to do explore the free options available, and I eventually came across a few options. I found a proprietary API for both the MLB and NHL, that were free, and very in depth. The issue that arose was: at the heart of the extension is the leagues, and I wanted to make sure that all major sports leagues are supported.

If I chose to use a proprietary API, I would essentially be creating an extension for only one league, contradicting the goal of this extension. Since I wasn't able to find a free API for many of the other major leagues, which would essentially bring my project to a halt, I looked for more options.

Thankfully, I came across some well documented ESPN API endpoints that were free, with no limits for requests. Thus, I ended up choosing the ESPN API, it offered a similar JSON response for each league and a simple way to scale out each command for every league.

## Conclusion

This project has been an invaluable learning experience. Every challenge and every experience strengthened my problem solving skills and introduced me to new concepts and technologies. Building this project with the goal of real world use and implications, has been incredibly rewarding, and I'm excited iterate further upon this concept in the future, providing an unrivaled sports experience for Raycast.
