---
layout: grid-container
title: Saving and reusing data in Trap Kit
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style: projection-text
next: Interactivity activity
---

# {{ page.title }}

- You can simulate a lot by just reusing data people enter in a form
- To enable saving on a page, add `save-data: true` to the front matter
- Retrieving data uses "get this, put it here" syntax
- Let's look at an example: [Create account template]({{ site.baseurl }}{% link templates/create-account.md %})

```
{% raw %}{% include components/text-input.html label="Full name" type="text" %}{% endraw %}

{% raw %}{% include actions/get-data.html get-this="create-your-account-full-name" put-it-here="full-name" %}{% endraw %}

{% raw %}{% include components/text-input.html label="Email address" type="email" %}{% endraw %}

{% raw %}{% include actions/get-data.html get-this="create-your-account-email-address" put-it-here="email-address" %}{% endraw %}
```