---
title: "Sharing a Book"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
permalink: sharing-a-book.html
---

Book owners can share their books with individual users, groups, or even someone who has not registered in CX Studio yet. When sharing, you can choose between viewer- or editor-level access (Can View and Can Edit permissions, respectively).

## How to Share a Book

There are several ways to start sharing a book:

* When in Dashboard Explorer, expand the actions menu {% include inline_image.html file="icon-actions.png" %} next to a particular book and select **Share...**

   To share several dashboards or books at once, select them using the check boxes on the left. Multiple selections share the same actions menu. See [Bulk Sharing][sharing-a-book.html#bulk-sharing] below.

* When a book is open, click the **Share** button in the book header.

This opens the **Share Book** window, which lets you control who can access your book.

### To share a book

{% include note.html content="A [Share Edit][permissions] or Share [View permission][permissions] is required to perform this action." %}

1. Select **Notify via email** if you wish CX Studio to send an email notification in addition to on-site notification.

   Optionally, you can provide a custom notification message.

   {% include tip.html content="Notifications are sent only once. If you add new recipients to the list, only they will be notified." %}

1. Next, type a person's email or a group name into the field below.

   If you share a book with someone who has not registered in CX Studio yet, Clarabridge will send an email message with a link and login details, which will allow that person to create an account in CX Studio. Sharing via email gives a user read-only access to the book and grants a [CX Studio Basic license][license-types]. It is possible to modify user permissions after the registration.

   {% include note.html content="Inviting new users to CX Studio through sharing requires a [Create Users through Sharing][permissions] permission." %}

   {% include note.html content="Whenever you share your book with someone via a new email address, it uses up one of your CX Studio licenses. Please contact your Clarabridge Account Representative if you need to purchase more licenses." %}

   Use the **Find user or group in list...** field to search users who have already been granted access to this book.

   {% include tip.html content="Click the **+** icon next to the group name to expand a list of group members." %}

1. To share a book publicly (with everyone), click the globe icon or type **Public** in the subscribers field.

   {% include image.html file="share-public.png" %}

   Note that public sharing only assigns the **Can View** permission and does not trigger email notifications.

1. Select an appropriate permission (Can View or Can Edit) and click **Add**.

1. Add as many users and groups as you need and click **Update**.

## Dashboard Sharing vs. Book Sharing

Book sharing is similar to [dashboard sharing][sharing-a-dashboard]. Please note the following differences:

* Dashboard sharing and book sharing work independently.

   A user may not have access to an individual dashboard, and still be able to view it as part of a shared book.

* When sharing a book, Can View and Can Edit permissions only apply to the book, not the dashboards included in it.

## Group Sharing

When you share a book with a group, all members of that group will have access to your book. It does not matter when a user joins the group---users who join the group after you have shared your book will still get access to it. However, as soon as any user leaves the group, your book will no longer be accessible to that user.

You can [stop sharing your book][sharing-a-book.html#how-to-stop-sharing-a-book] at any time.

## Public Sharing

You can distribute starter or organization-wide books to every CX Studio user in your Master Account using the **Public** group. A public book is available in every user's dashboards list, including new users who register after the book is created.

You can combine public sharing with select user and group sharing.

## Bulk Sharing

You can share several dashboards or books at once. Select them in Dashboard Explorer using the check boxes on the left, then expand the actions menu {% include inline_image.html file="icon-actions.png" %} next to one of the selected items and click **Share...** Note that when sharing multiple objects, public sharing and "already shared with" information is not available.

Bulk sharing is additive, meaning that it never lowers user's existing access to any of the dashboards being shared.

When bulk sharing with a lower access, existing higher access remains:

{% include image.html file="bulk-share-can-view.png" %}

When bulk sharing with a higher access, existing lower access is upgraded:

{% include image.html file="bulk-share-can-edit.png" %}

## How to Stop Sharing a Book

You can stop sharing a book by opening the **Share Book** window as described above and removing users or groups from the **Already shared** list using the **x** icon.

When a book is shared with a group, removing a user from that group will also make your book inaccessible to that user.
{% include links.html %}
