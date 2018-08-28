---
title: "Restoring a Dashboard"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
toc: false
permalink: restoring-a-dashboard.html
---

Dashboard versioning lets you restore your dashboard to one of its previously saved states.

{% include note.html content="Only dashboard owners can access version management for their dashboards." %}

## To restore a dashboard

1. Open the dashboard you wish to roll back.

1. Expand the actions menu {% include inline_image.html file="dashboard-actions-icon.png" %} in the dashboard header and select **Versions**.

1. The dashboard enters the Versions mode (indicated by the **Dashboard Versions** header above) and shows the **Versions** panel.

   Here you can see all saved versions of the dashboard in reverse chronological order (current version is shown at the top).

   {% include image.html file="dashboard-versions-menu.png" %}

1. To view a certain version, click a corresponding entry in the Versions panel. This loads the previously saved version of the dashboard.

   {% include note.html content="Viewing previous dashboard versions makes no changes to your current dashboard." %}

1. If you wish to exit the Versions mode without making any changes, click the **Close** button in the top left corner.

1. To restore a certain version, select it in the Versions panel and click the **Restore this version** link.

   {% include image.html file="dashboard-versions-restore.png" %}

1. Confirm your action, and the version you selected will become the current one.

   {% include image.html file="dashboard-versions-restored.png" %}
