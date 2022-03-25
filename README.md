# 01-Code-Refractor
First week's bootcamp assignment

## Our task
For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## What we are working with: 

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

## Our products:

GitHub Repo: https://github.com/KIMOISQUIGGLES/01-Code-Refractor

Webpage: https://kimoisquiggles.github.io/01-Code-Refractor/

## Changes made:

1. `(HTML)` Renamed div tags to make them more legible.
   ```
   a. assigned Header, Body, and Footer
   b. assigned sections within Header (nav) and Body (article, aside)
   c. added classes and ids to tags to help consolidate CSS elements

   ```
2. `(CSS)` Cleaned up redundancy
   ```
   a. Consolidated redundant selectors
    -too many header h1
    -.header div ul {} and .header div ul li {}
    -benefit-lead, benefit-brand, benefit-cost
    -benefit h3
    -.online-reputation-management, .social-media-marketing, .search-engine-optimization
    -corresponding img selectors
    -h2 within <aside>
   b. changed class/id/names for selectors to match changes in HTML
   ```

