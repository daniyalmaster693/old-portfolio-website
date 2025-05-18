---
layout: ../../layouts/Project Page Layout.astro
pageTitle: "MenuScores | Daniyal Master"
title: "MenuScores"
description: "Live Scores. Right From Your Menubar"
date: "2025-05-18"
creator: "Daniyal Master"
order: "0"
---

<img src="/Screenshot 2025-05-18 at 9.55.35 AM.webp" alt="MenuScores Screenshot">

## Overview

MenuScores is a lightweight macOS menu bar app that brings sports and scores right to your desktop.

## Goals and Motivation

MenuScores was created to solve a personal need: a fast, non-intrusive way to follow my favorite sports without relying on bloated apps, slow websites, or distracting platforms. I wanted something that lives quietly in the menu bar, provides real-time updates, is configurable, and sends useful alerts when games start or finish.

Most sports apps and websites are ad driven, mobile only, and overloaded with unnecessary information and features. I just wanted something simple that could work on my Mac, and let me follow a game without having to open a website or pick up my phone.

A top priority was to build something that felt truly native to macOS: fast, clean, and lightweight. To make this happen, I challenged myself to learn Swift and SwiftUI by building a real world and useful tool, and thats how MenuScores came to life.

## Features

<img src="/Screenshot 2025-05-18 at 9.53.14 AM.webp" alt="MenuScores Settings">

- **Live Menubar Scores** - Pin games to your menu bar and receive real-time score updates available at a glance.
- **Smart Notifications** - Get notified when a pinned game starts or finishes.
- **League Control** - Choose which leagues are shown and stay focused on the sports you care about.
- **Configurable** - Configure notification types and refresh intervals to fit your preferences.
- **Lightweight & Native** - Built with Swift and SwiftUI for fast performance and seamless macOS integration.

## Supported Leagues

<img src="/Screenshot 2025-05-18 at 10.00.58 AM.webp" alt="MenuScores Screenshot">

- NHL
- NBA
- WNBA
- Men's College Basketball
- Women's College Basketball
- NFL
- MLB
- F1
- PGA
- LGA
- UEFA – UEFA Champions League
- EPL – English Premier League
- ESP – La Liga (Spain)
- GER – Bundesliga (Germany)
- ITA – Serie A (Italy)
- NLL

## Installation

**Requires macOS 13.0 and later**

- Download the latest release
- Move the app to your **Applications folder**
- Run the app.

**Note**: On first launch, macOS may warn that the app couldn't be verified. Click **OK**, then go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** to launch the app.

## Usage

<img src="/Screenshot 2025-05-18 at 9.55.47 AM.webp" alt="MenuScores Screenshot">

- After running the app, you'll be greeted with a walkthrough that will provide information about the different features of the app, and security and privacy concerns.
- **In order to use the notifications feature**, you must grant permission for MenuScores to send notification. An option will be presented to do so in the walkthrough screen.

- Clicking on the menubar title will show a list available leagues.
- Hovering over a league will show a dropdown of all the games for the day in that league.
- Clicking on a game will pin it.
- You can use the clear set game option, or click on a different game to clear the title.
- You can quit the app directly from the menubar, or open the preferences window to configure app behaviors (this can be done by pressing Cmd + , after opening the menubar component, or clicking the preferences button if your on macOS 14.0 and later).

## Dependencies

- <a href="https://github.com/sindresorhus/LaunchAtLogin-Modern" aria-label="Launch at login swift package" target="_blank">LaunchAtLogin Modern</a>

## Links

- <a href="https://github.com/daniyalmaster693/MenuScores" aria-label="MenuScores Github Repository" target="_blank">Github Repository</a>
- <a href="https://github.com/daniyalmaster693/MenuScores/releases/tag/Release" aria-label="MenuScores Releases Page" target="_blank">Github Releases</a>

## Tech Stack Used

- Swift
- SwiftUI

## Challenges and Solutions

One of the biggest challenges in building MenuScores was designing a real time experience that was lightweight. I needed to fetch and process live sports data at regular intervals without overwhelming the CPU or battery. To solve this, I built a configurable update system that tracks only the selected game and uses Swift’s async/await with efficient state comparisons.

Another key challenge was ensuring the app felt truly native to macOS. Many similar apps are Electron-based and feel out of place, and rely more heavily upon system resources. I intentionally built MenuScores in Swift and SwiftUI, working with macOS frameworks like MenuBarExtra, UserNotifications, and UserDefaults to create an experience that blends seamlessly with the OS.

Learning Swift as I went proved to be difficult especially with the different nuances of Swift compared to other languages and frameworks such as Javascript and Typescript. By working through the challenges and diving into documentation and examples, I developed a deeper understanding of Swift and applied what I learned to my app.

## Conclusion

<img src="/Screenshot 2025-05-18 at 9.56.12 AM.webp" alt="MenuScores Screenshot">

MenuScores started as a small personal project, but it’s grown into something I’m excited to share. I built it to solve a problem I had, and if it happens to solve that same problem for you, even better. I’m excited to continue refining it and welcoming any feedback along the way. This experience has taught me a lot, and I'm excited to continue to build solutions to real problems.
