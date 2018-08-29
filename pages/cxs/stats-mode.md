---
title: "Stats Mode"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
permalink: stats-mode.html
---

Widget stats mode provides request details and enables you to see the data behind your graphs.

{% include note.html content="Widget stats mode is available only for visualization-based widgets." %}

## To access widget stats mode

1. Open the dashboard in [Edit mode][editing-a-dashboard].

1. Expand the actions menu {% include inline_image.html file="icon-actions.png" %} in the top right corner of a widget and click **Stats**.

Stats mode displays the following information:

* **Dashboard.** The name of the dashboard.

* **Widget.** The name of the widget.

* **Time to Run.** The total time it took to run the report.

   A detailed breakdown is provided below for troubleshooting purposes.

   * **Delivery.** Shows how long it took to deliver the request from your browser to CX Studio, plus how long it took to deliver the reporting data from CX Studio to your browser. This is primarily a reflection of your Internet connection quality and speed.

   * **Processing.** Shows how long it took for CX Studio to process the request (check permissions, data access etc.) and formulate the appropriate request to the Content Provider, plus how long it took for CX Studio to validate the response it got from the Content Provider. This is primarily a reflection of CX Studio's responsiveness.

   * **Generation.** Shows how long it took for the Content Provider to query the dataset and aggregate the data requested by CX Studio. This is primarily a reflection of the Content Provider's responsiveness.

* **Request ID.** The ID of the request.

* **Cache.** The status of cache for this report.

* **Total Count.** The total number of records that match report conditions and filters (also displayed in the form of [n=total][using-the-n-total]).

* **Report data.** A simple table with report data.

Click the **Copy** button in the top right corner to copy widget stats to clipboard.

Click the **Back** button to return to your report.

{% include image.html file="stats-mode.png" %}
{% include links.html %}
