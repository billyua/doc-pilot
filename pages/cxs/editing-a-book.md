---
title: "Editing a Book"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
permalink: editing-a-book.html
---

After a book is [created][creating-a-book], you can change its properties and modify its tabs. Additionally, you can make quick changes to the dashboards within a book.

{% include note.html content="To edit a book, a user must have an [Edit Dashboard][permissions] permission and be granted [Can Edit][sharing-a-book] permission for the specific book." %}

There are several ways to edit a book:

* When in Dashboard Explorer, expand the actions menu {% include inline_image.html file="icon-actions.png" %} next to a particular book and select Edit.

* When viewing a book, click the **Edit Book** button in the book header.

   **Tip:** You can also edit a dashboard that is open in the current tab by clicking the **Edit Dashboard** button. After modifying a dashboard from within a book, you have two save options:

   * **Save And Return To Book.** Save your changes and return to viewing the book.

   * **Save.** Save your changes and return to Dashboard Explorer.

This opens the book builder, where you can modify its name, description, and tabs.

{% include image.html file="book-edit.png" %}

1. To rename a book or change its description

   Type the new name and description in the corresponding fields.

1. To add a tab

   Click the **+** icon on the right and select a dashboard for the new tab.

1. To unassign a dashboard from a tab

   Click the pencil icon in the **Dashboard Name** field.

   {% include note.html content="You can unassign a dashboard added by another user, but you will not be able to assign it back." %}

1. To assign a dashboard to a tab

   Click the name of the dashboard in the ALL DASHBOARDS section.

   {% include note.html content="You can only assign dashboards you own." %}

   {% include note.html content="If a dashboard you own is prevented from sharing, you cannot assign it to books owned by others." %}

1. To remove a tab

   Click the **x** icon inside it.

1. To rearrange tabs

   Drag and drop them where you need.

1. Click **Save** when done; auto-saving works only for dashboards, not for books.

## Assigning Your Dashboards to Books with Different Owners

Your ability to add a dashboard to a book depends on the following factors:

* Regardless of who owns the book, you can only add the dashboards you own.

* If you are the owner of the book, you can add any dashboard you own to it.

* If you are not the owner of the book, you can only add dashboards not prevented from sharing by the editors (**Prevent Editors from Sharing** setting is disabled in [dashboard properties][dashboard-properties]).

In other words, if your dashboard is prevented from sharing, you can add it to your own book (because in this case you can still control who gets access to it through [book sharing][sharing-a-book]), but not to a book owned by another user.

{% include note.html content="When someone is editing a shared book owned by another user and some of the dashboards in that book are prevented from sharing, *Not available* is shown instead of the dashboard's name. As a general rule, we do not recommend using dashboard prevented from sharing in books you plan to share." %}
{% include links.html %}
