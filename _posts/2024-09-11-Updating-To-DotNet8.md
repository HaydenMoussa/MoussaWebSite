---
layout: post
title: "Updating Arboretum Website to .Net 8"
author: "Hayden Moussa"
tags: DiscoTray
---

I ended off last week updating the arboretum website to .net 8. After that was finished Nicoli submitted a pull request that removed some of the unnessesary files that where used in .net 5 but not in 8. While looking at his pull request I realized that I was getting the same error that we had fixed on .net 5 last week. "5001 object object not found" so I spent some time trying to fix that. I still have not finished that but in the process of trying to figure that out I updated the TreePopUp class to use HttpClient to grab in images instead of HttpWebRequest.