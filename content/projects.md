---
title: Projects
date: 2022-11-24
menu: main
weight: 110
comments: false
---
## [Events Website](https://github.com/Mmesek/mEvents)
##### Python, FastHTML, Supabase, SQLAlchemy
###### 2025
Website to manage event registrations
- OAuth & Magic Link authorization with Supabase Auth
- Dynamically listing upcoming events, with participants counts
- Participation forms for organization
- Listing events from Discord server
- Deployed on [Render](https://mevents-vt2u.onrender.com/) & [Vercel](https://mms-events.vercel.app/)

## [Audio Transcriber](https://github.com/Mmesek/Audio-Transcriber)
##### Python, faster_whisper, ffmpeg, Docker
###### 2025
Tool to transcribe content, with channel-based speaker separation.

## [Portfolio Manager](https://github.com/Mmesek/database-library/portfolio)
##### Python, SQLAlchemy, SQL, matplotlib, pandas
###### 2025
Set of scripts to load crypto exports into a database for portfolio analysis
- Load exchange's export into a database according to a translation schema
- E-mail & API parsers
- Script to fetch NBP's previous day rate for tax calculations in Poland

## [Blog website](https://github.com/Mmesek/mmesek.github.io) and [Hugo Theme](https://github.com/Mmesek/Hugo-mTheme)
##### Hugo, HTML, CSS, Git LFS
###### 2024
You are here.

## [ItemsAPI](https://github.com/Mmesek/ItemsAPI)
##### SQL
###### 2021-2022
- Transactions based on Double Entry Accounting
- Entirely in SQL, with Supabase for serving REST API


## Anti Raid/Spam system for Discord server
##### Python
###### 2021
- Anti raid system to prevent users from joining server if their account had similiar age to account that joined previously ([Source](https://github.com/Mmesek/MBot.py/blob/4ed74e4391d8c57ced81a68263fc7161ec98388d/bot/infractions/anti_raid.py#L21-L25))
- Hijacked account detection based on same messages sent in multiple channels in short interval ([Source](https://github.com/Mmesek/MBot.py/blob/4ed74e4391d8c57ced81a68263fc7161ec98388d/bot/dispatch/actions.py#L176-L219))
- Spam accounts detection based on flagged keywords ([Source](https://github.com/Mmesek/MBot.py/blob/4ed74e4391d8c57ced81a68263fc7161ec98388d/bot/infractions/anti_raid.py#L63-L68))


## [Game Bundle manager](https://github.com/Mmesek/Game-Bundle-Manager)
##### Python, SQLAlchemy
###### 2020
Scripts to manage keys from across multiple game bundles.

## [Code generator](https://github.com/Mmesek/DocParser)
##### Python
###### 2020-2022
Code generator taking language template from JSON definition


## [Markdown parser](https://github.com/Mmesek/DocParser/tree/main/doc_parser)
##### Python
###### 2020-2022
Markdown parser creating JSON according to parsed tables


## [Command Framework](https://github.com/Mmesek/MFramework.py "MFramework's Github repository")
##### Python, SQLAlchemy, Redis, i18n
###### 2020-2024
Low boilerplate command framework for Discord bot developement

- Unified command invocation context
- Database support with SQLAlchemy
- Caching via Redis
- Internalization (i18n)


## [Discord API Wrapper](https://github.com/Mmesek/mdiscord "mDiscord's Github respository")
##### Python, Aiohttp
###### 2020-2024
Simple gateway client with event dispatcher & typecasting

- Extendible by registering event listeners with @decorators


## [Discord Bot](https://github.com/Mmesek/MBot.py "MBot.py's Github repository")
##### Python, SQLAlchemy
###### 2019-2024
Multipurpose event-driven bot with auto moderation, activity tracking & chat minigames


## [RSS Reader](https://github.com/Mmesek/RSSReader "RSSReader's Github repository")
##### Python, SQLAlchemy
###### 2019-2022
Script for parsing RSS entries into Discord Embeds

- Extensible by writing processing middle-wares
- Component-System based entry processors

Partially deprecated by [MiniRSS](https://github.com/Mmesek/MiniRSS) (2025) - Frontend for Miniflux that republishes RSS entries as a feed

## Prices Scrapper
##### Python, BeautifulSoup, TkInter
###### 2018
Simple multi-threaded web scrapper

- Tkinter GUI for listing price changes of observed items
