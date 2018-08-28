---
title: "Creating a Book"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: August 9, 2018
summary: "optional summary here"
sidebar: cxs
permalink: creating-a-book.html
---

To create a book, you need to provide a name for it and select the dashboards to include in it. You can add a single dashboard to multiple books.

{% include note.html content="A [Create Dashboard][permissions] permission is required to perform this action." %}

There are several ways to create a book:

* When in the Dashboard Explorer, click the **New Book** button in the ALL DASHBOARDS area.

* When viewing any book, expand the actions menu {% include inline_image.html file="dashboard-actions-icon.png" %} in the book header and select **New**.

* Alternatively, you can [duplicate an existing book][duplicating-a-book].

This opens the book builder, where you can define its properties.

{% include image.html file="book-create-01a.png" %}

1. Provide a name and optional description for your book.

   {% include note.html content="Book names must be unique per user." %}

1. Select a dashboard to be featured in your book on the first tab.

   {% include note.html content="You can only assign dashboards you own." %}

1. After you select a dashboard, its name is used as the name for the tab. You can provide a different name for the tab using the **Tab Name** field.

   {% include note.html content="The maximum length for a tab name is 50 characters. If a longer dashboard name is used, it will be truncated automatically." %}

1. To remove the selected dashboard, click the pencil icon in the **Dashboard Name** field.

1. To add one more tab to your book, click the **+** icon. You can add up to 20 tabs to one book.

   {% include tip.html content="Click the name of the tab to switch to it. The current tab is highlighted." %}

   {% include image.html file="book-create-02a.png" %}

1. To remove a tab, click the **x** icon inside it.

1. To rearrange tabs, simply drag and drop them where you need.

   {% include tip.html content="By default, the entry point for a book is the first tab (i.e. it will default to running the dashboard in the first tab)." %}

1. Click **Save** when done.

Books appear in the Dashboard Explorer with a book icon {% include inline_image.html file="icon-book.png" %} next to their names.
{% include links.html %}
