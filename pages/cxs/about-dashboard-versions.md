---
title: "About Dashboard Versions"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: about-dashboard-versions.html
---

Dashboard versioning in CX Studio keeps track of up to 20 of the most recently saved versions of your dashboard and lets you restore any of them.

Learn more:

* [How to restore a dashboard][restoring-a-dashboard]

* [How to save a version as a separate dashboard][saving-a-dashboard-version]

## What is a dashboard version?

A version is a snapshot of all the dashboard's widgets, applied filters, and personalization configuration. A dashboard version is created whenever your dashboard is saved (either when you click Save or via the auto-save).

{% include note.html content="Adding a widget to your dashboard via the menu, drilling, or copying, as well as deleting a widget triggers dashboard auto-save. Auto-save is NOT triggered when moving and resizing widgets." %}

## Does it matter who edits and saves a dashboard for version management?

A dashboard version is saved every time a user with appropriate permissions saves the dashboard. This can be a dashboard owner or a user with permissions to edit the dashboard. However, only dashboard owners can access version management for their dashboards.

## What happens to later versions after I restore an earlier version?

After a certain version is restored, CX Studio saves it as the current version and keeps the versions leading up to it. If there were 20 versions before the restore, the earliest one gets deleted from the system.

Consider the following example:

{% include image.html file="dashboard-restore.png" %}

## When I copy a dashboard, do its versions get copied as well?

No, only the current version of a dashboard gets copied.

## What happens when I transfer my dashboard to another person?

Only the current version of a dashboard gets transferred.

## Is dashboard versioning accessible from mobile devices?

No, you can only view dashboard versions and restore them when working on a desktop PC or a notebook.
{% include links.html %}
