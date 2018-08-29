---
title: "Grouping Data"
tags: [grouping, segment, group]
keywords: grouping, segment, group
last_updated: August 9, 2018
summary: "about grouping"
sidebar: cxs
toc: false
permalink: grouping-data.html
---

CX Studio lets you examine customer feedback from a variety of angles. When building a report, the first thing you need to do is specify the data you want to analyze. You can do this by **grouping**, **sorting**, and **filtering** your data.

In CX Studio, you can group data into meaningful segments using the following criteria:

* [Topics][grouping-data.html#topics]

* [Topic Leaf][grouping-data.html#topic-leaf]

* [NLP][grouping-data.html#nlp]

* [Words][grouping-data.html#words]

* [Associated Words][grouping-data.html#associated-words]

* [Enrichment][grouping-data.html#enrichment]

* [Language][grouping-data.html#language]

* [Time][grouping-data.html#time]

* [Attributes][grouping-data.html#attributes]

* [Metrics][grouping-data.html#metrics]

{% include tip.html content="In most reporting widgets you will find the grouping options in the **GROUP BY** drop-down list. Exceptions include a [Table report][table-widget], where you select data groupings in the GROUPINGS section and move them to the Applied Groupings section, and a [Heatmap report][heatmap-widget], where groupings are called BOXES." %}

## Topics

The **Topics** option lets you group data by the categories derived from customer feedback. Grouping data by topics provides an overview of what your customers are talking about the most.

Clarabridge assigns categories to sentences found in unstructured text using keywords and phrase patterns defined in classification models. For different categorization themes, you can select different classification models, as well as choose specific topics of interest within these models.

## Topic Leaf

Similar to Topics, the **Topic Leaf** option lets you group data by the categories derived from customer feedback. Topic leaves are just categories with no subcategories. Topics usually cover general,
high-level themes, while topic leaves provide more specific, lower-level subcategories.

{% include image.html file="tree-leaves.png" %}

Grouping data by topic leaves provides an overview of specific themes your customers are talking about.

## NLP

The **NLP** groupings are based on criteria automatically derived from unstructured feedback by the Clarabridge's Natural Language Processing engine.

### Words

The **Words** stack lets you group data by words or specific types of words mentioned in customer feedback.

* **All Words.** Group data by regular words. This will give you an idea of the most common terms customers are using when talking about your product or service.

* **CB Brand.** Group data by brand mentions.

* **CB Company.** Group data by company mentions.

* **CB Email Address.** Group data by email addresses mentioned in feedback.

* **CB Emoticon.** Group data by emojis and emoticons used in feedback.

* **CB Industry.** Group data by related industry.

* **CB Person.** Group data by names of people mentioned in feedback.

* **CB Phone Number.** Group data by phone numbers mentioned in feedback.

* **CB Product.** Group data by product mentions.

### Associated Words

The **Associated Words** option lets you group data by pairs of linguistically connected words mentioned in customer feedback. Associated words are presented in the following format: `word 1 --> word 2`, for example, `room --> clean`.

Grouping data by associated words provides an overview of the most common topics and themes being discussed by customers regardless of categorization.

### Enrichment

The **Enrichment** stack lets you group data by types of content detected in customer feedback.

* **CB Detected Features.** Group data by types of NLP features detected (for example, data containing industry or brand mentions).

* **CB Sentence Type.** Group data by the type of sentence (or intent) identified by Clarabridge (for example, CRY FOR HELP, REQUEST, or SUGGESTION).

* **Content Type.** Group data by it being Contentful or Non-Contentful as automatically identified by Clarabridge.

* **Content Subtype.** Further group Non-Contentful data by its subtypes (such as ads, coupons, article links, or "undefined" type). Note that for Contentful records, subtype is always Contentful as well.

### Language

The **Language** stack lets you group data by feedback language.

* **Auto-detected language.** Group data by languages automatically detected by Clarabridge (if language auto-detection is enabled for a project).

* **Processed language.** Group data by languages in which feedback was actually processed. Languages not supported by Clarabridge language detection are marked as OTHER. For a list of languages supported by Clarabridge refer to [Supported Languages][supported-languages].

## Time

The **Time** stack lets you group data by date and time.

First, you need to select a time attribute---**Document Date** is generally your go-to date, but other types of dates may be available in your feedback. Then, choose the periods you want to see (years, quarters, months etc.)

## Attributes

The **Attributes** stack lets you group data by the values of a selected structured attribute.

A structured attribute is any numeric or string field present in a record that is not the actual textual feedback. Structured attributes generally contain discrete data with a high degree of organization (such as a person's age or a product name). Particular attributes available for reporting depend on the source of feedback and usually vary from dataset to dataset.

## Metrics

The **Metrics** stack lets you group data by discrete values or bands of certain standard calculations and derived metrics. In other words, you can organize data by one metric and measure it by a different metric.

These groupings are provided out of the box:

* **Sentiment.** Group data by sentiment bands (negative, neutral, and positive). You can choose between 3 and 5 bands depending on whether you need to differentiate between negative and strongly negative, as well as positive and strongly positive feedback.

* **Effort.** Group data by effort bands (hard, neutral, and easy). Similarly to sentiment, you can choose between 3 and 5 bands depending on whether you need to differentiate between hard and very hard, as well as easy and very easy feedback.

* **CB Document Word Count.** Group data by the number of words in a document (record).

* **CB Sentence Quartile.** Group data by the quarter of the verbatim a sentence falls into (1, 2, 3, or 4). It can help you understand what is being discussed where in the conversation.

* **CB Sentence Word Count.** Group data by the number of words in a sentence.

In addition, you can define a Top Box, Bottom Box, or Satisfaction metric, and group data by their bands as well. These metrics help you determine whether feedback is
coming from a promoter, detractor, or a neutral customer.

* **Top Box** bands: Promoters and Other.

* **Bottom Box** bands: Detractors and Other.

* **Satisfaction** bands: Promoters, Neutrals, and Detractors.
{% include links.html %}
