---
title: Hello, Valaxy!
date: 2022-03-22
updated: 2022-03-23
categories: Valaxy Notes
tags:
  - valaxy
  - 笔记
---

## Hello, Valaxy!

```ts
import type { ThemeConfig } from 'valaxy-theme-moe'
import { defineConfig } from 'valaxy'

export default defineConfig<ThemeConfig>({
  // your theme name
  // valaxy-theme-moe name is 'moe'
  theme: 'moe',

  themeConfig: {
    banner: {
      enable: true,
      title: 'Moe的小站',
    },
  },
})
```
