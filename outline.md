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

- [Content]({{ site.baseurl }}{% link functionality/content.md %})
- [Components]({{ site.baseurl }}{% link functionality/components.md %})
- [Layouts]({{ site.baseurl }}{% link functionality/layouts.md %})
- [Templates]({{ site.baseurl }}{% link functionality/templates.md %})
- [Data]({{ site.baseurl }}{% link functionality/data.md %})
- [Functionality activity]({{ site.baseurl }}{% link functionality/activity.md %})

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

- [Codepen](https://codepen.io/)
- [GitHub](https://github.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [GitHub Pages](https://pages.github.com/)
- [Gitpod](https://www.gitpod.io/)
- [Jekyll](https://jekyllrb.com/)
- [jQuery](https://jquery.com/)
- [Liquid filters](https://shopify.github.io/liquid/filters/abs/)
- [Lowcode Lounge](https://lowcodelounge.co)
- [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) (GitHub-flavored)
- [Trapkit](https://trapkit.co/)
- [U.S. Web Design System](https://designsystem.digital.gov/)
- [VS Code](https://code.visualstudio.com/)



<hr>{: .border-primary}

{% capture site_baseurl %}
{{ site.baseurl }}/
{% endcapture %}

{% include components/button.html link=site_baseurl label="Back home" style="usa-button usa-button--big bg-accent-warm-light text-ink hover:bg-accent-warm-dark margin-bottom-2" %}
{: .text-ink}