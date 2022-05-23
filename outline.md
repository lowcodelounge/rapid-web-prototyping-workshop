---
layout: grid-container
title: Outline
body-style: bg-primary-darker text-accent-warm-lighter line-height-body-4 padding-bottom-9 font-body-lg slide
layout-style:
---

# Workshop Outline

Here's a tentative outline of the material we're going to cover.

Have questions? [Tweet at me](https://tiny.one/pn8bdvwr)
{: usa-intro}

<hr>{: .border-primary}

## Introduction

- [Why low-code prototyping?]({{ site.baseurl }}{% link introduction/why-low-code-prototyping.md %}) (was: rapid web prototyping 😬)
- [When to use]({{ site.baseurl }}{% link introduction/when-to-use.md %})
- [What you'll learn in this workshop]({{ site.baseurl }}{% link introduction/what-youll-learn.md %})
- [What you'll need]({{ site.baseurl }}{% link introduction/what-youll-need.md %})
- [What you'll build]({{ site.baseurl }}{% link introduction/what-youll-build.md %})
- [Introduction activity]({{ site.baseurl }}{% link introduction/activity.md %})

## Environment

- [GitHub]({{ site.baseurl }}{% link environment/github.md %})
    - [Branches]({{ site.baseurl }}{% link environment/branches.md %}), [commits]({{ site.baseurl }}{% link environment/commits.md %}), and [pull requests]({{ site.baseurl }}{% link environment/pull-requests.md %}), oh my!
- [Trapkit]({{ site.baseurl }}{% link environment/trapkit.md %}): the low-code prototyping toolkit
- [Gitpod]({{ site.baseurl }}{% link environment/gitpod.md %}): browser-based dev environment to save us from local installs
- [Markdown]({{ site.baseurl }}{% link environment/markdown.md %}): structured content, for both humans and computers
- [Environment activity]({{ site.baseurl }}{% link environment/activity.md %})

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

## Building

- Pick a project
- Set up a repo
- Share progress

## Resources

- [GitHub](https://github.com/)
- [GitHub Pages](https://pages.github.com/)
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