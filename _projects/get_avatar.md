---
layout: project
title: GetAvatar
website: https://www.getavatar.info/
website_pretty: getavatar.info
summary: Extract email from Gravatar images
logo: /assets/img/projects/get-avatar.png
date: 2016-07-09
tools:
  - JavaScript
  - MD5
  - Web Workers
---

GetAvatar attempts to derive a (supposedly) anonymous email address behind a given
[Gravatar](https://gravatar.com/) URL.

Gravatar uses an MD5 hash of the user's email address to display an avatar / profile picture.
If the user is registered on Gravatar, we can retrieve details from the Gravatar API and repeatedly
guess combinations of names against various email provider domains to try and find a match.

I built this as a proof of concept, showcasing the potential inherent (and unfixable?)
vulnerability in the Gravatar system. I'm pretty sure there's no justifiable use case!
