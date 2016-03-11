---
layout: post
title:  "NPM: Not a valid cache tarball name"
date:   2016-03-11 12:17:24 -0300
categories: nodejs
---

El problema está en el directorio que se está usando como tmp.
Para dejar el valor de tmp por defecto, usar el siguiente comando:

```
npm config set tmp
```


