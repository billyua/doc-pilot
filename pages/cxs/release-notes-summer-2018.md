---
title: "What's New in Summer 2018"
tags: [sample1, sample2]
keywords: release notes, what's new, summer 2018
last_updated: August 9, 2018
summary: "What's New in Summer 2018"
sidebar: cxs
permalink: release-notes-summer-2018.html
---

## August 8, 2018

CX Studio has been updated with the following new capabilities:

### Full Sharing Disclosure

See all users and groups with access to your dashboards, whether they are shared directly or via a book. Dashboards can reach a larger audience via book sharing, and now that information is available in the **Share Dashboard** dialog.

### Security Audit for Books (Master Account Administrators)

Create, edit, delete, view, move, and rate books, as well as navigate between tabs are the actions available in the [Security Audit log][security-audit].

## July 25, 2018

CX Studio has been updated with the following new capabilities:

### Edit a Dashboard Directly from within a Book

If you are a dashboard editor, you can now click the Edit Dashboard button upon viewing a dashboard as a tab in a book. After making changes, click Save And Return To Book to navigate back to your starting point.

### "Save and Share" for Filters and Metrics

When you create new or edit existing filters or metrics, click **Save and Share** to share the new or modified object right away. You'll need the Share Filter and Share Metric permissions.

### Manage Dashboard Schedules

New actions are available for scheduled events in the Dashboard Schedules section:
  * **Disable.** Cancels all scheduled runs.
  * **Modify.** Launches the dashboard schedule dialog to modify it, or to add up to 5 schedules.
  * **View All Runs.** Lists all the runs of the schedule, with their status (Completed, In Progress, Failed), with most recent runs at the top.

### Update Group Membership in Fewer Clicks

When creating or editing a group, go to the MEMBERS tab and search for users to add to the group with the **+** icon, and simply click **x** to remove a user.

## July 11, 2018

CX Studio has been updated with the following new capabilities:

### Dashboard Explorer Updates

Folders are now always displayed at the top, followed by dashboards and books in alphabetical order. There is a new dashboard icon ({% include inline_image.html file="icon-dashboard.png" alt="" %}), and the favorite icon ({% include inline_image.html file="icon-favorite.png" alt="" %}) is now always visible in front of dashboards and books.

### Do More with Less Clicks

Select multiple dashboards at once, and perform these actions: move them all to a folder, hide or show them, delete dashboards or books you own.

### Filter Attribute Values Based on Whether They Exist or Not

The option to choose "Exists" or "Does Not Exist" is now available in dashboard, widget, saved filters, and Filtered metric conditions for attributes. "Exists" will filter on records with any values for that attribute, while "Does Not Exist" will filter on records that do not have a value for that attribute. This simplifies reporting on "Volume of documents with no City value" or "Volume of documents with a City value," as well as creating Filtered metrics for survey questions based on Answered/Not Answered criteria.

### User Management Made Simpler

The option to delete groups derived from an Organization Hierarchy is now available when said Organization Hierarchy is deleted.

## June 27, 2018

CX Studio has been updated with the following new capabilities:

### Hide Dashboards and Books

Declutter your Dashboard Explorer by [hiding dashboards and books][hiding-dashboards-and-books] you rarely use or do not wish to see at all. You can switch the visibility of hidden items on and off, as well as unhide these items any time you need.

### Clear Changes in Dashboard Filters

We added the **Clear Changes** option to the dashboard filters drop-down list to make it easier to cancel your changes and revert to previously applied filters. It is available both when viewing and editing a dashboard.

### New Dashboard Actions Menu

The dashboard actions menu was replaced with a hamburger menu {% include inline_image.html file="dashboard-actions-icon.png" alt="" %} that is now a standard CX Studio interface element to contain all settings and available actions both for widgets and dashboards. We also organized the menu items into easier to use sections, and migrated the Layout ribbon's options here.

### Persistent Folder State

From now on whenever you open a dashboard from inside a folder and then navigate back to Dashboard Explorer, the folder will remain open unless the session times out.

### Display More Attributes in Alerts

Alerts can now display up to 30 attributes, which are selected in [Account Settings][about-master-accounts].

## June 13, 2018

This is the Summer 2018 release of CX Studio. On top of bug fixes and general improvements across all CX Studio features, these are the new capabilities:

### Multi-Level Widget as Filter

We expanded the [Widget as Filter feature][widget-as-filter] to allow linking three or more widgets in a parent-to-child-to-grandchild filter relationship. This literally lets you take data exploration and on-the-fly discovery to the next level!

### Bulk Actions with Widgets

Selecting multiple widgets by shift-clicking now lets you perform these bulk actions:

* Duplicate them inside the current dashboard.
* Copy them to a new dashboard or any other dashboard to which you have editor's access.
* Refresh them.
* Delete them.
* Push them to top or bottom of a dashboard.
These actions are available for 2.0 reporting widgets as well as these content and layout widgets: text block, label, image, and video.

### Books (Tabbed Dashboards)

Meet the most requested feature on our Ideas Forum: [books, or tabbed dashboards][about-books]! This feature lets you bundle up to 20 dashboards into a single thematic "package" that recreates a browser-like experience.

### More Dashboard Filters

You can now add up to 15 dashboard filters to a single dashboard.

### Scatter Widget Quadrants

You can now highlight problem areas in a [Scatter plot][scatter-widget] using custom colors and label quadrants, and call for action on the points that need attention.

### Do More with Less Clicks

We implemented drag and drop controls to let you quickly perform the following actions:

* Rearrange dashboard filters (this is especially useful if you have up to 15 filters to manage).
* Reorder calculations and groupings in widget definitions.

### Set Your Favorite Project and Forget It

You can opt to set your favorite Content Provider, account, and project in [user preferences][user-preferences], to use as defaults for all new objects: dashboards, widgets, metrics, and filters.

### Enhanced Dashboard Explorer

We enhanced the Dashboard Explorer by adding these new capabilities:

* Create a dashboard inside a folder directly from that folder's options menu.
* Export a dashboard to PDF directly from the Dashboard Explorer, without having to view the dashboard.

### Governance for Books, Filters, and Metrics

We made the following enhancements to the way books, filters, and metrics are handled in relation to user management:

* When removing users, you can now transfer ownership of their books, filters and metrics, in addition to dashboards.
* You can now share metrics with Public or specific users/groups.
* The Dashboard Sharing report now includes data on both books and dashboards, as well as the dashboards that are part of each book.
{% include links.html %}
