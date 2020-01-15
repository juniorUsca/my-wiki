---
title: useEffect Comparation
description: 
published: true
date: 2020-01-15T10:09:00.259Z
tags: react
---

# useEffect Comparation

useEffect en react hace una comparacion para ejecutar el efecto solo cuando haya algun cambio en el array del segundo parametro que le enviamos

El problema es que solo soporta datos primitivos y casos muy puntuales, pero no comparacion de objetos.

Para arreglarlo usamos normalmente `useMemo` en el objeto y asi react reconoce que es el mismo objeto,
ya en el useMemo se usan parametros mas detallados segun se necesite

#### Posibles soluciones
https://github.com/facebook/react/issues/14476#issuecomment-471199055
