---
title: "Dashboard Filters Visibility"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: dashboard-filters-visibility.html
---

Dashboard-wide filter visibility depends on the type and status of the filter, user's access level, and selections made by dashboard editors. This topic covers how these factors affect filter visibility.

## All Dashboard Filters

For all dashboard filters, selections [saved in Edit mode][defining-dashboard-filters] are preserved and preselected when dashboard viewers open a dashboard. Viewers can toggle those selections at will unless a filter is locked.

## Date Ranges

**Out-of-the-box date ranges** (like "Last 180 days" or "Current month") are always available to all dashboard viewers.

**Custom date ranges** are visible if any the following conditions are true:

* A filter is created by or shared with the user.

* A filter is preselected in Edit mode.

## Saved Filters

The Saved Filters selection includes filters created in CX Designer and CX Studio.

**Out-of-the-box sentiment filters** (like "Negative Sentiment (predefined)") are always available to all dashboard viewers.

Other **CX Designer shared filters** are visible if any of the following conditions are true:

* A user has access to the source project on the Content Provider side.

* A filter is preselected in Edit mode.

**Filters created in CX Studio** are visible if any of the following conditions are true:

* A filter is created by or shared with the user.

* A filter is preselected in Edit mode.

## Topics

**Topic filters** are always visible to all viewers on behalf of the dashboard owner.

## Attributes

**Attribute filters** are always visible to all viewers on behalf of the dashboard owner.
{% include links.html %}
