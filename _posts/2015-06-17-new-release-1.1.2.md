---
layout: page
title: New release - 1.1.2
redirect_from: "/new-release-1-1-2/"
---

There have been awhile since our last post. Today we want to tell about improvements we made for this time.

#### We released several new features:

**Filter by milestone.** Now you can filter cards by milestones (with “^milestone name” notation).

![Filter by milestone]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-12-34.png)

**Filter by label.** Now you can filter cards by labels (with “~label name” notation).

![Filter by label]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-10-51.png)

**Autocomplete in filter.** Now filtering is much easier with simple autocomplete.

![Autocomplete in filter]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-19-30.png)

**Hide archived projects.** Only active projects are visible on boards list.

**Edit issue.** Now you can edit issue title and description from the board.

![Edit issue]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-12-55.png)

**More cards on board.** We increased number of cards on board from 50 to 100.

**GitLab links.** Now you can navigate to issue in GitLab from issue on board. We added links to GitLab issue from issue view on board.

![GitLab links]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-13-44.png)

**Multiline comments.** We changed comment input from “text” to “textarea”, now you can write multiline comments with ease.

![Multiline comments]({{ site.url }}/content/images/2015/06/Screen-Shot-2015-06-17-at-19-14-18.png)

#### And also several bugfixes ;)


- We showed a noisy alert when websocket connection failed requiring you to reload the page. Now page reload automatically on websocket connection fail.

- We fixed docker images versions, “latest” tag was used in several images before, leading to unpredictable updates at some conditions.

- We reduced websocket server image size about 4 times, now updates and deployments should be notable faster.
