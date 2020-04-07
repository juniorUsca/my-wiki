---
title: CSS: Margin Collapse
description: 
published: true
date: 2020-04-07T19:43:13.407Z
tags: margin, css
---

# Css: Margin Collapse

El margin collapse se da cuando 2 margenes estan cercanos.

Los margenes **no aplican collapse** cuando:
 - El padre tiene uno de las siguientes configuraciones:
```css
- position: absolute; 
- position: fixed; 
- overflow: hidden; or
- overflow: scroll;
```
