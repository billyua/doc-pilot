---
title: "Personalizing a Dashboard"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: personalizing-a-dashboard.html
---

## What Is Dashboard Personalization?

Dashboard personalization lets you tie widget reports to the structure of your organization or market segmentation. Widgets in a personalized dashboard are automatically filtered according to the selected organization hierarchy and the currently logged-in user's highest position in that hierarchy.

{% include note.html content="The main prerequisite to personalizing a dashboard is having at least one active organization hierarchy. Refer to the Organization Hierarchy section to learn more." %}

For example, an executive will see reports based on all the data (without any filters), with an option of slicing report data down to any of the underlying business segments (regions, stores, and so on). At the same time when a regional manager opens the same dashboard, report data will be limited to a corresponding region. This way people will only see the data that is relevant to them.

Below is an example of a personalized dashboard using a 3-tier hierarchy:

{% include image.html file="personalization-ehill-expanded.png" %}

Here is how dashboard personalization works:

* Different users see different report results on the same dashboard if they are in different parts of the organization hierarchy.

* A corresponding business segment is shown in the dashboard header.

* If a user is assigned to a hierarchy level that is not the lowest, that user can toggle between leaf levels of the hierarchy. A user with access to the highest level of a hierarchy can select all subsequent business segments.

* If a user is NOT identified in the hierarchy, that user will see ALL the data and be able to toggle between leaf levels of the hierarchy.

## How to Enable Dashboard Personalization?

1. Open your dashboard.

1. Expand the actions menu in the dashboard header and select **Edit Dashboard Properties**. This opens the **Dashboard Properties** window.

1. Select the **Enable Personalization** check box and then choose one of the active [organization hierarchies][about-organization-hierarchy] from the drop-down list.

1. Click **Save**.
{% include links.html %}
