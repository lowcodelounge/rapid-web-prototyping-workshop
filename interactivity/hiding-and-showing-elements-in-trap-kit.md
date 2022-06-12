---
layout: grid-container
title: Hiding and showing elements in Trap Kit
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style: projection-text
next: Saving and reusing data in Trap Kit
---

# {{ page.title }}

- You can simulate a lot by just hiding and showing things
- Both actions use simple "click this, hide/show this" syntax
- Let's look at an example: [Subscribe template]({{ site.baseurl }}{% link templates/subscribe.md %})

## Example

```
# Subscribe to our mailing list

{% raw %}{% include components/alert.html type="success" heading="Success" text="Thank you for subscribing. You’ll hear from us soon!" %}{% endraw %}

{% raw %}{% include components/text-input.html label="Email" type="text" %}{% endraw %}

{% raw %}{% include components/button.html label="Subscribe" link="#" %}{% endraw %}

{% raw %}{% include actions/show.html click-this="subscribe" show-this="success" focus-this="close" %}{% endraw %}

{% raw %}{% include actions/hide.html click-this="close" hide-this="success" %}{% endraw %}
```
