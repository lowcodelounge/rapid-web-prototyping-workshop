---
layout: grid-container
title: Components
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style: projection-text
next: Layouts
---

# {{ page.title }}

- Components from U.S. Web Design System
- Set up in Trap Kit template as `includes`
    - Reusable
    - Cleaner content files
    - Easily configurable
- [Component kitchen sink](https://trapkit.co/docs/component-kitchen-sink.html)

<pre>
{% raw %}{% include components/checkbox.html labels="This applies|Also this one|Don’t forget about me" %}{% endraw %}
</pre>

```
<fieldset class="usa-fieldset">
  <legend class="usa-legend">Select any historical figure</legend>
  <div class="usa-checkbox">
    <input
      class="usa-checkbox__input"
      id="check-historical-truth"
      type="checkbox"
      name="historical-figures"
      value="sojourner-truth"
      checked="checked"/>
    <label class="usa-checkbox__label" for="check-historical-truth">Sojourner Truth</label>
  </div>
</fieldset>
```