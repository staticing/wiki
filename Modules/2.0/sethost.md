---
title: Modules &raquo; m_sethost
layout: default
---

## Description

This module allows opers to modify their [Virtual Host](virtualhost.md) while connected to IRC. 

## Configuration Tags

To use this command an oper must have `SETHOST` specified in either their o:line's `<class:commands>` tag or the 
`<oper:commands>` tag.

## Commands

Command | Oper-Only | Chanop-only | Description
------- | --------- | ----------- | -----------
`/SETHOST <host>` | Yes | N/A | Changes the issuer's [Virtual Host](virtualhost.md) to `<host>`


## User Modes

This module implements no user modes.

## SNOMASK

This module implements no server notice masks.

## Channel Modes

This module implements no channel modes.

## Extended Bans

This module implements no extended bans.

## Special Notes

None.
