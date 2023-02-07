---
title: TIL - How I Fixed Endless Sharp Module Errors in Gatsby
date: 2023-02-07
tags:
  - til
  - gatsby 
layout: layouts/post.njk
---

Dear Future Jeff,

The next time your Gatsby dependencies fall apart like stairs falling down stairs, you might just try this (which just worked for us).

<code>
  brew remove vips
  rm -rf node_modules
  yarn install
</code>

We found this <a href="https://stackoverflow.com/questions/67560211/mac-m1-something-went-wrong-installing-the-sharp-module">here</a>.

I'm certain we've actually had and solved this problem before, so that is why I'm just going to leave this note for you.


