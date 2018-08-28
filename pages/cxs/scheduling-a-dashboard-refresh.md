---
title: "Scheduling a Dashboard Refresh"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
toc: false
permalink: scheduling-a-dashboard-refresh.html
---

You can schedule a dashboard refresh to periodically rerun all of the dashboard's reports in the background and cache their results. Cached reports will be served faster as long as the cache remains valid.

## To schedule a dashboard refresh

1. Open a dashboard, expand the actions menu {% include inline_image.html file="dashboard-actions-icon.png" %} in the dashboard header, and select **Schedule**.

   Alternatively, you can schedule actions from the Dashboard Explorer by expanding the actions menu {% include inline_image.html file="icon-actions.png" %} next to your dashboard and selecting **Schedule** from there.

1. Click **Add Schedule** in the **Dashboard Scheduling** window.

1. Define schedule properties:

   * **Enabled.** Select this check box to enable the scheduled action. Clear it to temporarily disable this action.

   * **Starts on.** Define the date and time when the action should be triggered first.

      {% include note.html content="Your schedule will be automatically disabled six months after the start date. You can renew it for another six months at any time by clicking the **Renew** link." %}

   * **Frequency.** Define how often this action should be triggered.

   * **Action.** Select the **Refresh** option.

   * **Notify via.** Select how the users who have access to the dashboard should be notified each time a scheduled refresh finishes.

   * **Message.** Provide a custom message for the notification.

1. Click **Save**.

1. Optionally, click **Add Schedule** to schedule more actions. You can add up to 5 independent schedules per dashboard.

1. Make sure to save every schedule you added.

1. Close the **Dashboard Scheduling** window.

See also:

* [Refreshing Report Data][refreshing-report-data]

* [How Caching Works][how-caching-works]
{% include links.html %}
