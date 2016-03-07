---
layout: page
title: Advanced filtering and board settings
---

We are proud to roll out a new 1.5.0 release!

#### This release features:

**Improved filtering system.** Now filter works with OR condition within group and AND condition with multiple groups. Basically if you will select "bug" and "feature" labels, only cards that have "bug" OR "feature" labels displayed on the board, and if you additionally select the milestone the cards that have those labels AND selected milestone will be displayed.

![Improved filtering](/content/images/2016/03/2016-03-07-improved-filter.png)

**Board settings.** Now you can configure stages from within the board.

![Board settings](/content/images/2016/03/2016-03-07-board-settings.png)

**Improved modile experience.** Now mobile version is more user friendly including board controls layout and card view.

To update - just get new binary from our [downloads page](http://kanban.leanlabs.io/downloads) replace an old one and reload an app, or just pull new docker image [leanlabs/kanban:1.5.0](https://hub.docker.com/r/leanlabs/kanban/), update docker-compose.yml with new image version and restart the containers.
