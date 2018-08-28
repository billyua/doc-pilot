---
title: "Dashboard Filters Logic"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: dashboard-filters-logic.html
---

This topic explains how filters selected at different levels apply to your data.

## Multiple Selections in a Single Filter Drop-Down

For any single dashboard filter drop-down, when multiple values are selected, the following logic applies:

* AND between saved filters

   For example, **CITY: Boston + Negative Sentiment** will only return results that match both filters (records with negative sentiment from Boston).

* OR between topics

   For example, **Happiness + Surprise** will return results that match either topic (any mentions of either happiness or surprise).

* OR between attribute values

   For example, **REGION: West + REGION: East** will return results that match either value (any records from either the West or East region).

{% include image.html file="single-multi-selection.png" %}

## Multiple Filter Drop-Downs

Each dashboard filter relates to other dashboard filters with an AND condition.

You can add the same categorization model twice in different filter drop-downs. For example, if you add Happiness and Surprise topics in different drop-downs, this will only return results where happiness and surprise are mentioned together.

{% include image.html file="multiple-dds-topics.png" %}

## Dashboard Filters and Widget Filters

Dashboard-wide saved filters, attribute, and topic filters relate to widget-specific filters with an AND condition.

Dashboard-wide date range completely replaces widget-specific date range filters.

{% include image.html file="dashboard-vs-widget-filters.png" %}
