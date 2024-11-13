---
layout: post
title: "Microsoft Entra + Database Troubles"
author: Ryan Fuller
excerpt: "One step at a time."
---
I started off the week by working on trying to rename the database to "Resources" instead of "Textbooks". While making it, I just named it Textbooks because it fell in line with the tutorial more, and so it just kinda made more sense to ensure I wasn't going to be messing anything up. But I really should've just read between the lines and made sure it was named Resources, because now renaming it is causing all sorts of weird issues.

Firstly, it says that the table just doesn't even exist, which just shouldn't be true. I'm not sure why, but nothing I can find makes any sense on how to fix it. I'll just need to do more research.

Secondly, if I rename it to Resources instead of Textbooks, the URL to access the database pages is still https://localhost/Textbooks. This remains constant no matter how many references to the phrase "Textbooks" are changed (even when I changed all of them). So, next week, I'm gonna just double down and figure out exactly what's going on with the name of the address and how to adjust it to match the actual name of the database that is to come.

Zoie added Microsoft Entra authentication to the website, but it's a bit broken right now. Elliot found a local fix (switching ClientCredentials to ClientSecret in a json file), but we'll have to figure out what to do about it during tomorrow's meeting. Either way, a pretty productive week that helped me hone my troubleshooting skills!