---
title: Modules &raquo; m_watch
layout: default
---

## Description

Adds the `/WATCH` command, which is used by clients to maintain notify lists. The `/WATCH` command is a more 
efficient replacement for `/ISON` which consumes less bandwidth. 

## Configuration Tags

This module does not implement any configuration directives.

## Commands

`/WATCH [ <C|S|L>|<+/-nick> ]`

Adds or deletes a user from the watch list 

Examples:

* Add `luser` to the watchlist:
 * `/WATCH +luser`
* Remove `luser` from the watchlist:
 * `/WATCH -luser`

## User Modes

This module does not implement any user modes.

## SNOMASK

This module implements no server notice masks.

## Channel Modes

This module does not implement any channel modes.

## Extended Bans

This module does not implement any extended bans.

## Special Notes

Usually this command is used directly by client software and not by users. The parameter `C` is an extension used by 
mIRC to clear the watch list (and therefore must be supported), and the parameter `S` is an extension also used by 
mIRC to query the watch list status.