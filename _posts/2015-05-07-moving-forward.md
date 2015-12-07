---
layout: page
title: Moving forward
redirect_from: "/moving-forward/"
---

Two months ago was our initial release. We got a lot of feedback and have implemented several new features.

Today we are proud to announce about 1.0.7 release of LeanLabs Kanban with several improvements:

**Simplified URI scheme.** You can navigate to board by “namespace/reponame” in URI (e.g. demo.kanban.leanlabs.io/boards/leanlabsio/kanban)

**Cards ID in URI are GitLab issues ID.** Example: [demo.kanban.leanlabs.io/boards/leanlabsio/kanban/cards/18](https://demo.kanban.leanlabs.io/boards/leanlabsio/kanban/cards/18) and [gitlab.com/leanlabsio/kanban/issues/18](https://gitlab.com/leanlabsio/kanban/issues/18).

**Simplified Tab navigation in browser window.**

![Simplified URI scheme]({{ site.url }}/content/images/2015/05/Screen-Shot-2015-05-07-at-14-51-10.png)

**You can filter card by user name.** We implemented simple filter by username for cards on board with “@” annotation. To show only cards assigned to user with name “user” you can type “@user” in filter field and press “Enter”. To show all cards that have assignee you can simply type “@”.

![You can filter card by user name]({{ site.url }}/content/images/2015/05/Screen-Shot-2015-05-07-at-14-41-14.png)

**Simplified validation rules when creating a card reflecting GitLab rules.** Now you can leave “Description” blank when creating card.

**Fast cards close.** We added "Close" button for cards in last column. You don't need open card for to close it.

![Fast cards close]({{ site.url }}/content/images/2015/05/Screen-Shot-2015-05-07-at-14-46-16.png)

We are pleased that our project moves forward, we hope that these updates will be useful to you.
