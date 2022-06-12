---
layout: grid-container
title: Styling in Trap Kit
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style: projection-text
next: Styling activity
---

# {{ page.title }}

- Use design tokens and utility classes
- Three levels:
    - Component (include)
    - Layout (div container)
    - Page (body)
- Example template: [Create account]({{ site.baseurl }}{% link templates/create-account.md %})
- Add custom CSS if needed

## Component (single)

```
{% raw %}{% include components/icon.html icon="info" size="4" style="text-info-dark float-left margin-right-1" %}{% endraw %}
```

## Component (multiple)

```
---
layout: centered-column
text-input-style: radius-lg padding-3 border-2px border-base
---
```

## Layout and page

```
---
layout: centered-column
body-style: bg-base-lightest
layout-style: tablet:width-tablet bg-white margin-top-6 padding-5 radius-lg shadow-3
---
```