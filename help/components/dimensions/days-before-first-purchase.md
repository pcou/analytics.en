---
title: Days before first purchase
description: The number of days between a visitor's first visit and their first purchase.
---

# Days before first purchase

The 'Days before first purchase' dimension reports the number of days that pass between the first time a visitor reaches your site and when they make a purchase. For example, if a visitor makes a purchase one day after first visiting, then any subsequent visit or event belongs to the "1 day" dimension value.

After a visitor makes their first purchase, they belong to the same dimension value for the remainder of the visitor's cookie lifetime.

## Populate this dimension with data

Adobe automatically populates this dimension based on the [`purchase`](/help/implement/vars/page-vars/events/event-purchase.md) event in your implementation. If you implement the `purchase` event on your site, this dimension always works.

## Dimension values

Dimension values include the number of days between a visitor's first visit to your site and their first purchase. Each number of days is a separate dimension value, with "Same day" occurring where a visitor's first visit and their first purchase happened on the same day.
