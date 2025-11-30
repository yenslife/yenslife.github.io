---
author: 海狸大師 (yenslife)
title: "數學排版"
date: 2019-03-08
description: "設定 KaTeX 的簡要指南"
math: true
draft: true
---

Hugo 專案中的數學符號可以透過使用第三方 JavaScript 函式庫來啟用。

<!--more-->

在這個範例中我們將使用 [KaTeX](https://katex.org/)

- 在 `/layouts/partials/math.html` 下建立一個 partial
- 在此 partial 中參考 [Auto-render Extension](https://katex.org/docs/autorender.html) 或在本地主載這些腳本
- 像這樣在您的範本中包含此 partial：

```bash
{{ if or .Params.math .Site.Params.math }}
{{ partial "math.html" . }}
{{ end }}
```

- 要全域啟用 KaTeX，請在專案配置中將參數 `math` 設定為 `true`
- 要在每個頁面的基礎上啟用 KaTeX，請在內容檔案中包含參數 `math: true`

**注意：** 使用 [支援的 TeX 函式](https://katex.org/docs/supported.html) 的線上參考

{{< math.inline >}}

{{</ math.inline >}}

### 範例

{{< math.inline >}}

<p>
行內數學：\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>

{{</ math.inline >}}

區塊數學：

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
