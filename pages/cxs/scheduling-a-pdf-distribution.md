---
title: "Scheduling a PDF Distribution"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
toc: false
permalink: scheduling-a-pdf-distribution.html
---

You can schedule a periodic email distribution of a dashboard's PDF snapshot to a selected group of recipients.

Email recipients do not have to log into CX Studio to view the updated dashboard; they can simply view the PDF. However, recipients have to be registered in CX Studio to be able to receive the emails.

## To schedule a PDF distribution

1. Open a dashboard, expand the actions menu {% include inline_image.html file="dashboard-actions-icon.png" %} in the dashboard header, and select **Schedule**.

   Alternatively, you can schedule actions from the Dashboard Explorer by expanding the actions menu {% include inline_image.html file="icon-actions.png" %} next to your dashboard and selecting **Schedule** from there.

1. Click **Add Schedule** in the **Dashboard Scheduling** window.

1. Define schedule properties:

   * **Enabled.** Select this check box to enable the scheduled action. Clear it to temporarily disable this action.

   * **Starts on.** Define the date and time when the action should be triggered first.

      {% include note.html content="Your schedule will be automatically disabled six months after the start date. You can renew it for another six months at any time by clicking the **Renew** link." %}

   * **Frequency.** Define how often this action should be triggered.

   * **Action.** Select the **Distribute PDF via Email** option.

   * **Send test email to me.** Click this link to receive a test email with current settings before starting a proper distribution.

   * **Distribution.** Select the distribution method.

      * **Specific users and groups** option lets you add individual users and groups to the distribution list.

         {% include note.html content="If your dashboard is [personalized][personalizing-a-dashboard] and the user you add to the distribution list is part of the organization hierarchy applied to the dashboard, the PDF will honor that user's hierarchy level (regardless the distribution method)." %}

      * **Organization Hierarchy** option lets you use the organization hierarchy to define who should receive the emails. Every user will receive a personalized version of the dashboard for the highest hierarchy level available to them.

   * **PDF Name.** Provide a name for the PDF file.

      {% include tip.html content="Type the curly bracket **{** to access a list of available placeholders you can use in **PDF Name**, **Email Subject**, and **Email Body** fields." %}

   * **Email Subject.** Provide a custom subject for the emails.

   * **Email Body.** Provide a custom message for the emails.

1. Click **Save**.

1. Optionally, click **Add Schedule** to schedule more actions. You can add up to 5 independent schedules per dashboard.

1. Make sure to save every schedule you added.

1. Close the **Dashboard Scheduling** window.
{% include links.html %}
