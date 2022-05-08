---
layout: grid-container
title: Home
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style:
---

# Workshop Outline

Here's a tentative outline of the material we're going to cover.

Have questions? [Tweet at me](https://tiny.one/pn8bdvwr)
{: usa-intro}

<hr>{: .border-primary}

## Introduction

- Why low-code prototyping? (was: rapid web prototyping 😬)
- When to use
- What you'll learn in this workshop
- What you'll need
- What you'll build

## Environment

- GitHub
    - Branches, commits, and pull request, oh my!
- Trapkit: the low-code prototyping template
    - U.S. Web Design System
    - Jekyll and Markdown
    - GitHub Pages
- Other tools:
    - Codepen
    - Gitpod
- Activities:
    - Sign in to GitHub
    - Create copy of template and publish

## Functionality

- Components
- Layouts
- Templates
- Content
- Data
- Activity:
    - Create a signin flow

## Styling

- USWDS primer
- Design and utility tokens
- Styling in Trapkit
- Activity:
    - Customize signin flow

## Interactivity

- jQuery primer
- Actions in Trapkit
    - Hiding and showing things
    - Saving and resuing data
- Conditionals

## Build

- Potential projects:
    - CDC Quarantive and Isolation Calculator
    - Verifly digital identity app
    - Flight check-in
    - Something of your choice

## Resources

- [GitHub](https://github.com/)
- [Gitpod](https://www.gitpod.io/)
- [Codepen](https://codepen.io/)
- [U.S. Web Design System](https://designsystem.digital.gov/)
- [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) (GitHub-flavored)
- [Jekyll](https://jekyllrb.com/)
- [jQuery](https://jquery.com/)
- [VS Code](https://code.visualstudio.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [Liquid filters](https://shopify.github.io/liquid/filters/abs/)

<hr>{: .border-primary}

{% capture site_baseurl %}
{{ site.baseurl }}/
{% endcapture %}

{% include components/button.html link=site_baseurl label="Back home" style="usa-button usa-button--big bg-accent-warm-light text-ink hover:bg-accent-warm-dark margin-bottom-2" %}
{: .text-ink}