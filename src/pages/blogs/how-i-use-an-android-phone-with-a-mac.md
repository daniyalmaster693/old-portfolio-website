---
layout: ../../layouts/Blog Post Layout.astro
pageTitle: How I use an Android phone with a Mac
title: How I use an Android Phone with a Mac
pubDate: "2025-03-02"
readingTime: 6 Min
---

<img src="/apple-ecosystem.webp" alt="Apple Ecosystem">

## Introduction

The apple ecosystem is arguably the number one reason people choose to get an iPhone over an Android. The experience is seamless, it's easy, it's connected, it just works. But not everyone wants an iPhone, and I wanted to share how I use my android phone with my Mac.

## Key Functionality of the Apple Ecosystem

The main features people enjoy through the apple ecosystem are:

- Airdrop
- Air Play
- Synced Clipboard History, Logins, Notes, etc
- Handoff
- iCloud
- iMessage and Facetime
- Apple Pay
- And more!

Many of these features work so well between devices because of the control apple has. Each device has built in protocols that allow them to essentially talk to each other in a secure yet seamless way. However, this only applies if your using an iPhone. Android users have an overall terrible experience out of the box.

## Apps

### Airdrop Alternative

<img src="/Localsend.webp" alt="Localsend Mac">

Let's start with one of the biggest and best features of the apple ecosystem: Airdrop. Seamless wireless file sharing, that is fast, just works, and is easy to use. The best alternative I've found and used is Localsend. Although I did find Blip was also a good option, although it require an account to use.

Localsend is a free and open source file sharing app. It is cross platform (works on Mac, Windows, Android, Ios, Linux), and requires an installation on both devices (in this case, the mac and the android phone). Once installed grant it the necessary permissions. Now, you can simply just select a file, text, or item from your clipboard, and share it with the other device (it will automatically scan your wifi network for devices, just make sure both are on the same network). Select the device, and it'll finish. This works for both large and small files, different formats, and works both ways. You can make it more seamless by adding devices to your favorites, and allowing them to automatically download files (removing the need to accept the transfer) from you favorite devices.

Since you can send text back and forth, it's a bit annoying, but it removes the need for a separate clipboard app.

### Airplay / iPhone Mirroring

<img src="/Scrcpy.webp" alt="Scrcpy Screen Mirroring">

Starting in Mac OS Sequoia (15) Apple added an iPhone Mirroring app that lets you control and mirror your display. It's a great feature and has plenty of great use cases. By far the best alternative is Scrcpy. It's another free and open source app that only needs to be installed on your Mac. Once installed, you'll need to enable usb debugging through the developer settings on your phone. That's it! You can follow the guide on the website, but since there is no gui, you must use the terminal. A bit annoying, and takes a bit of work to get this going, but once it does it works great. Performance will depend on your phone, but works best when using the wired version.

The app allows you to mirror your screen, audio, camera, use your keyboard and mouse as inputs, and more. It's overall great, and can be configured to work in different ways.

### iMessage and Photos

The ability to easily access your chats across any apple device is very useful. It allows you to receive and copy verification codes without opening your phone, or responding to texts. Fortunately, we have a very simple solution provided by Google for this. Using the Google Messages Web App, you can access all your chats once you pair your devices. It allows all the same functionality, including viewing messages, responding to texts, and more. In addition, it also allows for sms texting, which I believe the messages app doesn't provide (not 100% sure on this). You can take this further by creating a Safari Web app so you can easily access it at any time.

Having your photo library automatically synced is very useful for quickly accessing photos, and enabling more seamless workflows for things like photography. If you use the Google Photos App on your phone, it will automatically sync your photos to the web version, which you can then access on your mac.

### iCloud

This is a simple one. One your phone, if you head to the files app, you probably already have google drive built in (depends on the manufacturer and app). If you install the desktop version of drive onto your Mac, you can easily access your drive files from any device. And a bonus is that Google Drive gives you 15 gb of free storage, compared to iCloud which gives you 5.

### Facetime and Notes

Facetime is really useful especially on the Mac, and can be done through Google Meet. Although not it's not the nicest experience, and probably the one with the most friction to get going, it works fine, and can be used on your Mac and phone.

<img src="/Obsidian.webp" alt="Obsidian Note">

Apple notes automatically syncs notes across your devices, which is useful for note takers. You can do the same with Google Keep, or you could use a different app such as Obsidian, and take advantage of Google Drive by storing your Obsidian Vault inside a drive folder. This is a great way to sync your notes, without having to use an additional app, and provides an alternative to Apple Notes.

### Safari and Passwords

Having your browser history and everything synced is a nice to have feature, but imo isn't really useful (at least for me). Thus, I use Safari on my Mac, and Samsung Internet on my phone. For passwords, if you choose to use Chrome on both devices, then you can use the google passwords app to sync your passwords.

## Conclusion

Overall, while Android phones will never be supported and work well with apple devices, these workarounds should provide simple methods to still use some of your favorite apple ecosystem features. And if your an iPhone user who wants to jump to the other side, hopefully this guide will provide an easier way to use your devices together. If your an existing android user who uses a Mac, hopefully these apps improve your experience!
