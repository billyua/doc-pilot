---
title: "About Dashboard Filters"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: about-dashboard-filters.html
---

In addition to [widget filtering][filtering-a-widget] you can apply filters to an entire dashboard---that is, to every reporting widget within the dashboard.

## Available Filter Types

CX Studio lets you filter dashboards using the following filters:

* **Date Range.** Define a unified date range for an entire dashboard. Date ranges are applied to all dashboard widgets regardless of their source. See [Date Range Filters][date-range-filters] for available options.

* **Saved Filters.** Apply one of the following filter types:

   * Predefined sentiment filters

   * Shared or personal filters from CX Designer

      {% include note.html content="We recommend using shared CX Designer filters if you plan to share your dashboard with others." %}

   * Filters [created in CX Studio][creating-a-filter]

* **Topics.** Filter data by topics from a classification model.

* **Attributes.** Filter data by structured attribute values.

See [Dashboard Filters Logic][dashboard-filters-logic] to learn how filters selected at different levels apply to your data.

See [Dashboard Filters Visibility][dashboard-filters-visibility] to learn how access to Content Provider and other factors affect filter visibility.

## Filtering in Different Dashboard Modes

### Filtering in View Mode

When you change dashboard filters' values in View mode, it only applies to your current dashboard session. You can try any filter combination without affecting other users. It only applies to what you see and what you export. Reload a dashboard to reset dashboard filters to their default values.

See [Using Dashboard Filters][using-dashboard-filters] for details.

### Filtering in Edit Mode

If you wish to choose different types of filters for a dashboard or change their default values for all dashboard viewers, you need to do this in Edit mode.

See [Defining Dashboard Filters][defining-dashboard-filters] for details.

## How Dashboard-Wide Filtering Works

Here is an overview of how dashboard-wide filtering works:

* When filtering by attributes or topics, you can only use attributes or topics from the default project selected in [dashboard properties][dashboard-properties].

* Date filters are applied to all dashboard widgets regardless of their source.

* You can apply up to 15 filters to one dashboard.

* Filter values [selected in Edit mode][defining-dashboard-filters] are set as default values and affect all users who view the dashboard.

* Filter values [selected in View mode][using-dashboard-filters] allow you to slice and dice your data without affecting other users.

* Filters can be used together with [personalization][personalizing-a-dashboard], which means you can have a total of 16 elements in the dashboard filters panel: organization level and up to 15 additional filters.

* The order in which filters are added does not affect how the filters are applied. You can use the order of the filters as a visual cue to prioritize their importance.

* We do not recommend using dashboard-wide filters in combination with widgets from different projects, as it may produce unexpected results.

{% include links.html %}
