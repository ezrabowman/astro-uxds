---
tags: components
path: /components/select
date: Last Modified
layout: components.template.njk
title: Select
demo: https://astro-components.netlify.com/iframe.html?id=components-form-elements--select-menu
storybook: components-form-elements--select-menu
height: 130px
theme: true
---

# Select Menu

When activated, Select Menus allow users to select a value from a list of values. Once a value is selected, the Select Menu displays the selected value.

:::note

Drop Down menus were renamed Select Menus in Astro 4.5 to align more closely with the [W3C element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select) and Astro’s CSS class names.

:::

## Rules of Thumb

- Select Menus should display a list of multiple values.
- Select Menus may default to a state that instructs users what to do. For example: “Select Modem” or, a default choice like “Modem X.”
- When user knows what they’re looking for in advance, consider using a text field with client-side auto-complete functionality instead.

## Examples

:::two-col

![Don’t: Create a Drop Down list with too many options. The user needs to be able to scan and navigate the list easily](/img/components/dropdown-dont-1.png "Don’t: Create a Drop Down list with too many options. The user needs to be able to scan and navigate the list easily")

:::
