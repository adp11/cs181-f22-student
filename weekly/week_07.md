# Planning for Week 7

## High Level Topic Summary

  - Hierarchical Data Model
      - JSON and XML Formats
      - Procedural Traversals of trees (JSON and XML)
      - Declarative traversals of trees using XPath (XML)

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Section 15.4 | none
Tuesday    | Sections 16.1-16.2 | 16.5
Wednesday  | Section 16.3 | none
Friday     | Sections 16.4.1-16.4.3, 16.4.7 | none

## Progression

Last week, we introduced the hierarchical data model and JSON, one of the two most common formats for representing hierarchical data.  We can immediately understand some of the procedural (tree) operations on JSON data, as it only relies on nested Python data structure, which we have seen before.

This week, we extend our discussions to include XML, and then consider procedural tree operations for both JSON and XML data.  By the end of the week, we will extend our study of XML operations to include `XPath` as a declarative alternative to the procedural traversal and access operations we've seen using `lxml`'s `etree` module.

Monday: Discuss XML as an alternative hierarchical data representation.

Tuesday: Complete software lab on using JSON with Python, as well as JSON procedural operations.

Wednesday: Extend discussion of hierarchical procedural operations to XML-based data structures.

Friday: Introduce XPath for declarative XML operations.

---

## Projected Homework

HW | Day Assigned  | Day Due (by 11:59pm) | Contents
:--|:--------|:--------|:------------
[HW_3.a](../hw/HW_3.a/README.md) | Friday (10/7) | Monday (10/9) | JSON
[HW_3.b](../hw/HW_3.b/README.md) | Monday (10/10) | Wednesday (10/12) | XML
[HW_3.c](../hw/HW_3.c/README.md) | Wednesday (10/12)  | Friday (10/14) | XML procedural operations
[HW_3.d](../hw/HW_3.d/README.md) | Friday (10/14) | Friday (10/21) | XPath

__Note__: Because of Fall Break on Monday 10/17 and Tuesday 10/18, the homework based on Friday's class (10/14) will not be due until the following Friday.

## Tuesday Software Lab

In the [seventh software lab](../sw_lab/lab_07/README.md), we'll practice working with JSON via JSON-based COVID-19 data processing.