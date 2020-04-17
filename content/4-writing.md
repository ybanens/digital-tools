---
title: Writing
nav: true
---

# Phase 4: Writing

## Words on a page

{% capture text %}Plain text editors are much more important than you might think. Get yourself a good one.{% endcapture %}
{% include alert.md text=alert color=secondary %}

## ✏️ Text editors

***Recommended****
 - [Sublime Text](Windows) (https://www.sublimetext.com)
 - [Notepad++](https://notepad-plus-plus.org/)
 - [BBEdit (Mac)](https://www.barebones.com/products/bbedit/)

***Other tools***
 - [Atom](https://atom.io)
 - [Brackets](http://brackets.io)

### Markdown editors

Markdown is a simple and popular text formatting syntax. It's worth becoming familiar with it. This site is written in Markdown.

***The tools****
 - [Stackedit](https://stackedit.io)
 - [Dillinger](https://dillinger.io)
 - [Ulysses](Mac/iOS) (https://ulysses.app)
 - [Marked 2](Mac) (https://marked2app.com)

### 📓 Composition

***Recommended***

 - [Scrivener](https://www.literatureandlatte.com/scrivener/) - designed for long-form writing
 - [LaTeX](https://www.overleaf.com) - very flexible and robust; automatic journal submission
 - [Hemingway Editor](http://hemingwayapp.com/) - style checker

***Other tools***

 - [Microsoft Word](https://www.office.com) - popular—ubiquitous, almost—but not always the best tool
 - [Manuscripts](https://www.manuscriptsapp.com)
 - [Authorea](https://www.authorea.com) - 'Google Docs for scientists', automatic journal submission

# Create Lesson Content

Edit the lesson Markdown files to create content pages.

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.
The basics are intuitive, you can learn in about a minute!
See [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html) to get started.

When creating content pages:

- create/edit content pages in the `content` directory.
- to include a page in the nav, add `nav: true` to the file's yml front matter.
- the `title:` value will appear in the nav, sorted in the order of filenames. For simplicity use leading numbers in the lesson page filenames to create correct order.
- the default layout does not add `title` to the page, so that it can be a short for the nav. So add a title in the Markdown content.

## Components Includes

`workshop-template-b` contains a series of [Liquid "includes"](https://jekyllrb.com/docs/includes/) to add basic [Bootstrap components](https://getbootstrap.com/docs/4.1/components/) to your Markdown content.
Examples below demonstrate the includes.

--------

#### Figures 

`{% raw %}{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}{% endraw %}`

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}

----------

#### Alerts

`{% raw %}{% include alert.md text="This is a Bootstrap [Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}{% endraw %}`

{% include alert.md text="This is a [Bootstrap Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}

-----------

#### Link Buttons 

`{% raw %}{% include button.md text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}{% endraw %}`

{% include button.md text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}

---------

#### Cards

```{% raw %}
{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.md text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}{% endraw %}
```

{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.md text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}

------------

#### Modal

`{% raw %}{% include modal.md button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}{% endraw %}`

{% include modal.md button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}
