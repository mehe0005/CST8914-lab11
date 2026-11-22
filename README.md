# CST8914 Lab 11

## Question 1: What keyboard interaction is missing?

After testing all keyboard interactions such as space, enter, tab, shift + tab to open close and navigate the panels seems all interactions are already supported since native buttons are used.

## Question 2: What ARIA is missing?

The accordion was missing the `aria-expanded` and `aria-controls` attributes. I also added `role="region"` and `aria-labelledby` to the content panels for screen reader users.
