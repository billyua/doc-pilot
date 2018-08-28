---
title: "Defining Dashboard Filters"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
toc: false
permalink: defining-dashboard-filters.html
---

When your dashboard is in Edit mode, you can add up to 15 [dashboard-wide filters][about-dashboard-filters].

You can define default values for the filtering options or leave them empty for your dashboard viewers to select. The only exception is the date range, which cannot be empty.

You can also lock preselected filter values if you do not want dashboard viewers to change them.

{% include note.html content="This action requires [Can Edit][sharing-a-dashboard] permission for the dashboard, [Create Filter][permissions] user permission, and access to the dashboard's default project in the [Content Provider][linking-a-user-to-a-content-provider]." %}

## To define dashboard filters

1. Make sure default project is selected in [dashboard properties][dashboard-properties].

1. Open the dashboard in Edit mode by clicking the **Edit** button.

1. Expand the filters drop-down panel by clicking the filter button {% include inline_image.html file="icon-filter-dashboard.png" %} next to your dashboard's name.

1. Click **Add Filter**.

1. Expand the **Filter** drop-down list and select a filtering option.

   * **Date Range.** Filter all widgets by a [date range][date-range-filters].

   * **Saved Filters.** Apply predefined sentiment filters or [filters created in CX Studio][creating-a-filter].

   * **Topics.** Select a classification model and one or more topics to filter feedback by. Click the **Model** link below the search field to select an entire model and return all data classified into it (including root node rules, if any).

   * **Attributes.** Select an attribute to filter widgets by its values. You have two additional options for every attribute:

      * **Exists.** Return all data where the selected attribute has any value.

      * **Does Not Exist.** Return all data where the selected attribute does not have a value.

1. Once the filtering option is selected, you can expand the drop-down list and select the default value to filter dashboard reports by, if needed. This value will be preselected when anyone opens your dashboard.

1. To apply currently selected filters as defaults and preview filtering results, click **Apply**.

1. To cancel your changes and revert to previously applied filters, click **Clear Changes**.

1. To lock a filter, click the open lock icon {% include inline_image.html file="icon-lock-open.png" %} so that it changes to a closed lock icon {% include inline_image.html file="icon-lock-closed.png" %}. Locked filter's values cannot be changed in View mode.

1. You can add up to 15 total filter conditions.

   Note: The order in which filters are added does not affect how the filters are applied. However, you can arrange them the way you like. To do so, drag them up or down using the move icon {% include inline_image.html file="icon-move.png" %} on the left. You can use the order of the filters as a visual cue to prioritize their importance.

1. To remove a filter condition, click the **x** icon on the right.

1. Save your dashboard.

Filter values that you select in Edit mode serve as the default values for this dashboard whenever anyone opens or refreshes it.
{% include links.html %}
