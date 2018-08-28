---
title: "Duplicating a Dashboard"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
toc: false
permalink: duplicating-a-dashboard.html
---

CX Studio lets you duplicate dashboards created by you or by other users. The copied dashboard may look different from the original, because copying a dashboard changes [ownership][widget-ownership] of all the copied widgets to the user who does the copying. Consequently all data represented in these widgets is based on that user's Content Provider access.

What gets copied:

* [Dashboard properties][dashboard-properties] (except for the name and owner)
* [Personalization options][personalizing-a-dashboard]
* [Dashboard-wide filters][about-dashboard-filters] to which the new owner has access
* [Widgets][about-widgets] (their ownership changes)

What does not get copied:

* Private metrics and filters to which the new owner does not have access
* [Sharing options][sharing-a-dashboard]
* [Previously saved dashboard versions][about-dashboard-versions]

## To copy a dashboard

There are several ways of duplicating a dashboard:

* When in the Dashboard Explorer, expand the actions menu next to a particular dashboard and select **Duplicate**.
* When a dashboard is open, expand the actions menu in the dashboard header and select **Duplicate**.

After this CX Studio creates a copy of a dashboard and opens it in [Edit mode][editing-a-dashboard].
{% include links.html %}
