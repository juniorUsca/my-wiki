---
title: useContext Fix ReRender
description: 
published: true
date: 2020-01-15T10:09:00.259Z
tags: react
---

# useContext Fix ReRender

useContext en react devuelve un objeto con la informacion del contexto **dataContext**

El problema es que cualquier cambio que haya en el contexto asi sea una variable que el componente no usa obligara a
rerenderizar el componente, haciendo esto innecesariamente.

Para solucionar esto es mejor separar los contextos a solo las variables que normalmente se usan,
entonces es mejor tener varios contextos pequeños con pocas actualizaciones a un contexto grande y actualizaciones innecesarias.

#### Posibles soluciones
https://github.com/facebook/react/issues/15156#issuecomment-474590693
