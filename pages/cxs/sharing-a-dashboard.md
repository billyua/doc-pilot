---
title: "Sharing a Dashboard"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: cxs
permalink: sharing-a-dashboard.html
---

Sharing your dashboard allows you to collaborate on CX reports with others. You can share a dashboard with individual users, groups, or even someone who has not registered in CX Studio yet. When sharing, you can choose between viewer- or editor-level access (Can View and Can Edit permissions, respectively).

## How to Share a Dashboard

There are several ways to start sharing a dashboard:

* When in Dashboard Explorer, expand the actions menu next to a particular dashboard and select **Share...**
   To share several dashboards or books at once, select them using the check boxes on the left. Multiple selections share the same actions menu. See [Bulk Sharing][sharing-a-dashboard.html#bulk-sharing] below.
* When a dashboard is open, click the **Share** button in the dashboard header.
* When a dashboard is open, expand the actions menu in the dashboard header and select **Share**.

This opens the **Share Dashboard** window, which lets you control who can access your dashboard.

{% include image.html file="share-dashboard.png" %}

**To share a dashboard**

{% include note.html content="A [Share Edit or Share View][permissions] permission is required to perform this action." %}

1. Select **Notify via email** if you wish CX Studio to send an email notification in addition to on-site notification.

   Optionally, you can provide a custom notification message.

   {% include tip.html content="Notifications are sent only once. If you add new recipients to the list, only they will be notified." %}

1. Next, type a person's email or a group name into the field below.

   If you share a dashboard with someone who has not registered in CX Studio yet, Clarabridge will send an email message with a link and login details, which will allow that person to create an account in CX Studio. Sharing via email gives a user read-only access to the dashboard and grants a CX Studio Basic license. It is possible to modify user permissions after the registration.

   {% include note.html content="Inviting new users to CX Studio through sharing requires a [Create Users through Sharing][permissions] permission." %}

   {% include note.html content="Whenever you share your dashboard with someone via a new email address, it uses up one of your CX Studio licenses. Please contact your Clarabridge Account Representative if you need to purchase more licenses." %}

   Use the **Find user or group in list...** field to search for users who have already been granted access to this dashboard.

   {% include tip.html content="Click the **+** icon next to the group name to expand a list of group members." %}

1. To share a dashboard publicly (with everyone), click the globe icon or type **Public** in the subscribers field.

   {% include image.html file="share-public.png" %}

   Note that public sharing only assigns the Can View permission and does not trigger email notifications.

1. Select an appropriate permission (Can View or Can Edit) and click **Add**.

1. Add as many users and groups as you need and click **Update**.

## Can View vs. Can Edit

### Can View

Giving someone **viewer access** means that they will be able to view, refresh, and export your dashboard, but not make any changes to it.

{% include important.html content="CX Studio renders reports on behalf of their respective owners, not the users viewing it. It means that dashboard owners do not have to worry about the other users' data access level they will see the reports the same way the owner does." %}

### Can Edit

Giving someone **editor access** means that they will be able to make some changes to your dashboard, but not as much as the dashboard owner. The following actions are only available to the dashboard owner:

* Sharing a dashboard (unless this action is explicitly allowed in [dashboard properties][dashboard-properties] by clearing the **Prevent Editors from Sharing** check box)
* Deleting a dashboard
* Scheduling a dashboard
* Accessing dashboard versions
* Adding a dashboard to books

## Group Sharing

When you share a dashboard with a group, all members of that group will have access to your dashboard. It does not matter when a user joins the group users who join the group after you have shared your dashboard will still get access to it. However, as soon as any user leaves the group, your dashboard will no longer be accessible to that user.

You can [stop sharing][sharing-a-dashboard.html#how-to-stop-sharing-a-dashboard] your dashboard at any time.

## Public Sharing

You can distribute starter or organization-wide dashboards to every CX Studio user in your Master Account using the Public group. A public dashboard is available in every user's dashboards list, including new users who register after the dashboard is created.

You can combine public sharing with select user and group sharing.

## Bulk Sharing

You can share several dashboards or books at once. Select them in Dashboard Explorer using the check boxes on the left, then expand the actions menu next to one of the selected items and click **Share...** Note that when sharing multiple objects, public sharing and "already shared with" information is not available.

Bulk sharing is additive, meaning that it never lowers user's existing access to any of the dashboards being shared.

When bulk sharing with a lower access, existing higher access remains:

{% include image.html file="bulk-share-can-view.png" %}

When bulk sharing with a higher access, existing lower access is upgraded:

{% include image.html file="bulk-share-can-edit.png" %}

## Dashboard Sharing vs. Book Sharing

You can share a dashboard individually or as part of a book. Dashboard sharing and [book sharing][sharing-a-book] work independently. A user may not have access to an individual dashboard, and still be able to view it as part of a shared book.

You can see all users who have access to this dashboard at the bottom of the **Share Dashboard** window. They are organized into two stacks:

1. Users and groups with whom the dashboard is shared individually. You can modify their level of access (Can View or Can Edit) and remove them from this list entirely.

1. Users and groups with whom the dashboard is shared as part of the book. Book details are provided on the right. Book sharing only grants viewer-level access. To remove users from this list, you need to switch to book sharing.

{% include image.html file="already-shared-dashboard.png" %}

## How to Stop Sharing a Dashboard

You can stop sharing a dashboard by opening the **Share Dashboard** window as described above and removing users or groups from the **Already shared** list using the **x** icon.

When a dashboard is shared with a group, removing a user from that group will also make your dashboard inaccessible to that user.
{% include links.html %}
