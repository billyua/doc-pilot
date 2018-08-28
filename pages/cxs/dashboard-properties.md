---
title: "Dashboard Properties"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: dashboard-properties.html
---

Dashboard properties define its title, description, owner, Content Provider, sampling, and personalization settings.

To change dashboard properties, open it, expand the actions menu in the dashboard header and select **Edit Dashboard Properties**. This opens the **Dashboard Properties** window where you can modify the following parameters:

* **Dashboard Title.** Name your dashboard.
   {% include note.html content="Dashboard title must be unique per user per Master Account." %}
* **Folder.** Allows you to organize your dashboards [into folders][about-dashboard-explorer]. Empty folder means root (top level).
* **Dashboard Description.** Provide a brief description of your dashboard.
* **Dashboard Owner**. Defines the user who has full control over the dashboard. See [Changing the Dashboard Owner][changing-the-dashboard-owner].
* **Dashboard Optimization.** Lets you trade off some of reports' precision for better performance. See [About Dashboard Optimization][dashboard-properties.html#about-dashboard-optimization] below.
   * **On.** Better performance.
   * **Off.** Better precision. This is the default setting for newly created dashboards.
* **Enable Personalization.** Select this option to enable [personalization][personalizing-a-dashboard] and select the [organization hierarchy][about-organization-hierarchy] to use.
* **Prevent Editors from Sharing.** This option controls whether anyone else besides the owner is able to share this dashboard [individually][sharing-a-dashboard] or as [part of a book][sharing-a-book].
   * When this option is selected, the non-owner editors cannot share the dashboard. Moreover, it prevents the owner from adding this dashboard to shared books that are owned by other users. The owner is still able to add this dashboard to his or her books because only the owner can share a book.
   * When this option is cleared, the non-owner editors can share the dashboard as well as the owner. The owner is able to add this dashboard not only to his or her books, but also to shared books owned by other users.
* **Default Content Provider.** Choose a default Clarabridge CX Designer instance that will be inherited by all reporting widgets in this dashboard.
* **Default Account.** Choose a default Clarabridge CX Designer account that will be inherited by all reporting widgets in this dashboard.
* **Default Project.** Choose a default Clarabridge CX Designer project that will be inherited by all reporting widgets in this dashboard.
* **Default Color Palette.** Choose a default color palette for all reporting widgets that will be added to this dashboard in the future.

## About Dashboard Owners

A dashboard owner is a user who has full control over a dashboard. The user who created the dashboard is the first dashboard owner. CX Studio allows [changing dashboard ownership][changing-the-dashboard-owner].

Dashboard ownership means the following:

* Only an owner can [share a dashboard][sharing-a-dashboard].
* Only an owner can [schedule dashboard actions][about-dashboard-scheduling].
* Only an owner can manage [dashboard versions][about-dashboard-versions].
* [Copying (duplicating) a dashboard][duplicating-a-dashboard] does not copy its ownership. That is, if Paul copies a dashboard created by John, the new dashboard will be owned by Paul.

## About Dashboard Optimization

Dashboard optimization lets you improve performance of reports that use NLP aggregations (averages or sums for groupings like Words or enrichment attributes) by sacrificing their precision.

### When Dashboard Optimization is Enabled

For NLP-based groupings, averages and sums for metrics with less than 11 distinct values (i.e. OSAT, NPS, etc.) are performed using an estimated weighted average or sum. Estimated results typically have a low margin of error.

Averages and sums for metrics with greater than 11 distinct values (i.e. call duration, cost, revenue, etc.) are performed at the sentence level and may generate numbers skewed compared to record level stats based on the number of times a single record is duplicated in any one value of the NLP-based grouping.

### When Dashboard Optimization is Disabled

Aggregations for NLP-based groupings are calculated with higher precision.

{% include note.html content="Dashboard optimization is disabled by default. This behavior can be changed in [account properties][dashboard-optimization]." %}

## About Content Providers

A Content Provider defines the source of data for dashboard widgets.

Currently CX Studio supports the following Content Providers:

* Clarabridge CX Designer provides data for general reports
* Clarabridge Survey provides data for survey reports

{% include note.html content="Specific endpoints are defined by Administrators." %}

## About Personalization

A dashboard can either show the same data to all users or show different data to different users based on their position in the organization.

* When personalization is enabled, a dashboard shows different data to different users based on the filters assigned to them in the [organization hierarchy][about-organization-hierarchy].
* When personalization is disabled, the dashboard shows the same data to all users.

{% include links.html %}
