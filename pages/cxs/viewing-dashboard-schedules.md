---
title: "Viewing Dashboard Schedules"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
permalink: viewing-dashboard-schedules.html
---

The **Dashboard Schedules** section lets you view and manage [scheduled dashboard events][about-dashboard-scheduling].

To access this section, expand the main menu in the top right corner of CX Studio and select **Dashboard Schedules**. Note that at least one event must be scheduled before you can access schedule management.

{% include note.html content="Permission needed to access Dashboard Schedules: [Manage Settings][permissions]" %}

You can filter schedules by their respective dashboard owners or by the name of the related dashboard.

The table contains the following columns:

* **SCHEDULE.** Automatically created title of the scheduled event.

   {% include tip.html content="Click the schedule title to open its settings." %}

* **DASHBOARD.** The name of the related dashboard.

* **AUTHOR.** The owner of the related dashboard.

* **DATE UPDATED.** The date when the schedule was added or last modified.

* **MOST RECENT RUN.** The date of the last run or a dash if the event has not been triggered yet.

* **NEXT SCHEDULED RUN.** The date of the next scheduled run or a dash is the event has no remaining runs (when frequency is set to "Only Once").

Click the actions menu next to a scheduled event to perform one of the following actions:

* **Disable.** Cancel any scheduled runs, but keep the schedule in CX Studio.

* **Modify.** Change schedule settings, or add up to 5 schedules.

* **View All Runs.** View previous runs (time and status).
{% include links.html %}
