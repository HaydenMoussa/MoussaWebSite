---
layout: post
title: "Migrations and Locations"
author: "Hayden Moussa"
tags: DiscoTray
---

This week, I updated the pin location feature and the nearest tree location feature. When placing a pin on the map, it now differs from the pin used for trees. If no pin is on the map and you attempt to locate a tree based on the pin, an error message will appear.


I also began working on splitting the tree location into two columns: "Building" and "Direction." However, I encountered issues with migrations and database updates. The migrations are generating an unnecessary ASPNetRoles table, which is blocking the database update from running. I've spent this week troubleshooting that issue and implementing the location enhancements.


Thanks!