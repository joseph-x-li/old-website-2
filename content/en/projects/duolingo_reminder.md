---
title: Duolingo Reminder System
description: "Use Facebook Messenger to remind my friends to do their Duolingo Lessons."
toc: true
authors: []
tags: []
categories: []
series: []
date: 2021-12-27T14:42:09-08:00
lastmod: 2021-12-27T14:42:09-08:00
featuredVideo:
featuredImage:
draft: false
---
[Github](https://github.com/joseph-x-li/fb-duolingo)  

## About

Just do your Duolingo lessons so Duo won't come for your family.

<img src="/images/portfolio-5/duogun.jpg" width="700"/>


## How it works

The script is run daily using a cronjob. It calls Duolingo and Fbchat APIs to check streaks and send messages. Extendible to multiple users.

Random time delays are incorporated to prevent Facebook logging me out of my account.