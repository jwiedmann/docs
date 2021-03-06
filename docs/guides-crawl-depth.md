---
id: guides-crawl-depth
title: Limiting the depth of a crawl
sidebar_label: Limiting crawl depth
---

Use the parameter `maxHops` to specify the depth of your crawl from your seed URL(s). A value of `0` will limit crawling only to your seed(s). `maxHops=1` will spider all links from your seed URL(s); `maxHops=2` will follow the links on those pages; etc.

A `maxHops` setting of `-1` (default) will spider all links at any depth.

This can be used in conjunction with [URL crawl patterns](guides-patterns) to fine tune your crawl further.

