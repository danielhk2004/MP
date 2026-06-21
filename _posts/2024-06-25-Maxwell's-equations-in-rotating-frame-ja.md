---
title: "回転座標系におけるマクスウェル方程式"
categories:
  - Electromagnetic
tags:
  - Maxwell's equations
  - Rotating frame
permalink: /electromagnetic/Maxwell's-equations-in-rotating-frame-ja/
lang: ja
---
<style>
.language-switcher{
display:flex;
justify-content:flex-end;
gap:10px;
margin-bottom:25px;
}

.language-switcher a{
display:inline-flex;
align-items:center;
gap:6px;
padding:8px 14px;
background:white;
border:1px solid #dbeafe;
border-radius:999px;
text-decoration:none;
color:#1d4ed8;
font-weight:600;
font-size:0.9rem;
box-shadow:0 2px 8px rgba(0,0,0,.08);
transition:all .2s ease;
}

.language-switcher a:hover{
background:#eff6ff;
transform:translateY(-1px);
}
</style>

<div class="language-switcher">
  <a href="/electromagnetic/Maxwell's-equations-in-rotating-frame/">
    🇺🇸 English
  </a>

  <a href="/electromagnetic/Maxwell's-equations-in-rotating-frame-ja/"
     style="background:#1d4ed8;color:white;">
    🇯🇵 日本語
  </a>
</div>

<p style="color:#1e3a8a !important; font-weight:bold;">
回転座標系におけるマクスウェル方程式
</p>

<p align="center">
  <img src="/MP/assets/images/MXL.png" width="750">
</p>

---

本ノートでは、回転座標系におけるマクスウェル方程式の導出を試みる。この問題は、電磁気学および相対論の分野において重要な意義を有している。特に、この枠組みは非局所性（nonlocality）の研究対象として極めて興味深いものである。

本稿で用いる理論的枠組みおよび主要な結果の多くは、Kirk T. McDonald による *Electrodynamics of Rotating Systems* に基づいている。また、本ノートで得られる結論は、重力電磁気学（Gravitoelectromagnetism; GEM）との関連を考察する際や、フレームドラッギング現象を新たな視点から理解する上でも有用であると考えられる。

以下に、本ノートの基礎となった参考資料を示す。

[回転座標系におけるマクスウェル方程式]({{ site.baseurl }}/files/Electrodynamics%20of%20Rotating%20Bodies.pdf)
