---
title: CSS: Tips and trices
description: 
published: true
date: 2020-04-07T19:58:51.669Z
tags: margin, css, overflow
---

# Css: Tips and tricks

## Margin Collapse

El margin collapse se da cuando 2 margenes estan cercanos.

Los margenes **no aplican collapse** cuando:
 - El padre tiene uno de las siguientes configuraciones:
```css
- position: absolute; 
- position: fixed; 
- overflow: hidden; or
- overflow: scroll;
```

## Overflow

Use `overflow: scroll` to show a scrollbar in the box
Use `overflow: auto` to show a scrollbar only if it is necesary
