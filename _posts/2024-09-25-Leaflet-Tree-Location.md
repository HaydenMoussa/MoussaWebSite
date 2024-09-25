---
layout: post
title: "LeafLet and Finding the Correct Tree"
author: "Hayden Moussa"
tags: DiscoTray
---

This week, I continued working on the Hendrix Arboretum website. I built on last week’s enhancement of finding the nearest tree to the user and added a feature where the user can place a pin on the map to find the nearest tree to that pin. There are still some issues, though. While the pin appears on the map, and the "Find Nearest Tree" button does find a tree, it doesn't find the correct tree. Both the "Find Nearest Tree" and "Find Nearest Tree to Pin" buttons return the same tree, regardless of the user's location or the pin’s placement. Because of this, I believe there is an issue with my API call that's retrieving the trees. I am still investigating the issue, and that’s where I left off this week.