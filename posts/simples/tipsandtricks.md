---
title: CSS: Tips and trices
description: 
published: true
date: 2020-04-08T04:12:06.058Z
tags: margin, css, overflow
---

# Css: Tips and tricks

## Margin Collapse

1. El margin collapse se da cuando 2 margenes estan cercanos.
Solo se **aplican en vertical(top, bottom)**, no en horizontal (left, right)

2. Los margenes **no aplican collapse** cuando:
 - El padre tiene uno de las siguientes configuraciones:
```css
- position: absolute; 
- position: fixed; 
- overflow: hidden; or
- overflow: scroll;
```

3. Si un padre contiene hijos con margen, el padre solo ocupara hasta el borde de los hijos, para que el padre ocupe el margen incluido de los hijos, debe tener borde, padding o `overflow: hidden|auto|scroll`


## Overflow

By default use `overflow: visible`

Use `overflow: scroll` to show a scrollbar in the box
Use `overflow: auto` to show a scrollbar only if it is necesary

## Vertical align

Alinea el texto cercano respecto al elemento seleccionado

```css
	vertical-align: top | middle | bottom
```

Por ejemplo se aplica a la etiqueta `img` y el texto se pondra top, middle o bottom.
```html
<p>Curso de Desarrollo web online 2018 <img src="image"></p>
```