---
layout: layouts/post.njk
title: Apple Blocking PWAs on iOS is Not New
thumbnail: /img/uploads/youtube_is_a_pwa.png
alt: Youtube declared a PWA by lighthouse
tags: []
---
You might have read about Apple's [recent skullduggery](https://www.engadget.com/apple-confirms-home-screen-web-apps-will-no-longer-work-on-european-ios-devices-112527560.html#:~:text=It%20blames%20the%20EU's%20demand%20to%20support%20non%2DWebKit%20browsers.&text=Apple%20has%20explained%20why%20it's,recent%20iOS%2017.4%20beta%20releases.) with regards to blocking PWAs ([Progress Web Apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)) in the EU, in response to the [EU forcing apple to relinquish](https://www.nytimes.com/2024/01/25/technology/apple-app-store-europe.html) some control over their walled garden. But, near as I can tell, Apple has always, selectively, blocked PWAs. For example, if you don't love the YouTube app, and perhaps want to run it as a PWA (maybe you might use your own [tracker/ad blocking](https://apps.apple.com/af/app/vinegar-tube-cleaner/id1591303229) stuff), you cannot. You can save it to your home screen, but it will not open as PWA; instead opening as a tab inside of safari. Youtube is a PWA, according to my lighthouse test result (see image), so it would seem Apple is choosing not to honor it's status as PWA. I have not seen a reason as to why this would happen, but I would have to assume it has something to do with [Apple's business relationship to google](https://www.theverge.com/2023/10/26/23933206/google-apple-search-deal-safari-18-billion), and nothing to do with any valid technical reasons against it. I would love to be wrong about this.

To be clear, this is stupid and rotten and makes me feel trepidatious about my very Apple-centric tech stack.
