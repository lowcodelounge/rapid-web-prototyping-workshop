---
layout: grid-container
title: jQuery primer
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style: projection-text
next: Hiding and showing elements in Trap Kit
---

# {{ page.title }}

- Oldie but goody
- Makes you look smart without being a JavaScript expert
- Relatively straightforward syntax

## Examples

Change a button label:
```
<button id="pay" class="usa-button">Complete payment</button>

$('button#pay').html('Processing…')
```

<button id="pay" class="usa-button">Complete payment</button>

Change a button label after clicking it:
```
<button id="pay" class="usa-button">Complete payment</button>

$('button#pay2').on('click', function(){
    $('button#pay2').html('Processing…');
    $('button#pay2').attr('disabled', true);
});
```

<button id="pay2" class="usa-button">Complete payment</button>