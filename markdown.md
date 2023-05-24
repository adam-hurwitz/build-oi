---
title: 🖋️ Markdown
tags: about
description: Markdown
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">🖋️ Markdown</h1>

# About

#### Overview

- Format used for *[GitHub](https://docs.google.com/document/u/0/d/1W0pYNbK1a0teJDt96Jcli7RVEcaUpXpXoSKHbeX2VSs/edit) Readme.md* files, StackOverflow, and etc.
- Created by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) and [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz) in 2004
- There are many versions of Markdown with different features.
    - Use Markdown and/or HTML code that is universal across versions.

#### Resources

- [Wikipedia](https://en.wikipedia.org/wiki/Markdown)
- markdownguide.org: [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

# Topics

#### Indent sub-items

- Two or three spaces depending on the implementation
- An empty line break between items is required in some implementations

#### Images

- [Adding images to markdown pages with alt, title, height and width attributes](https://www.w3schools.io/file/markdown-images) *by W3Schools*
- Captions
    - Use italic text right after the image
    - Optionally

#### Center items

- [Markdown Center a Text, Image, Title, or Table](https://markdown.land/markdown-center) *by Markdown Land*
- _center_ HTML tag is deprecated
    - *See [The Centered Text element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center) by MDN*

#### Equality

- Greater than or equals
    - `$\ge$`
    - $\ge$
- Less than or equals
    - `$\le$`
    - $\le$

#### Embed

- [How can I embed a YouTube video on GitHub wiki pages?](https://stackoverflow.com/a/16079387/2253682) *on StackOverflow*

#### Represent keyboard input

- [&lt;kbd>: The Keyboard Input element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd) *by MDN*

#### Equation formatting

- In line
    - `$1 + 1$`
    - $1 + 1$
- Page centered
    - `$$1 + 1$$`
    $$1 + 1$$

#### Line break

- `<br/>`
- `\`
- *See [How to add new line in Markdown presentation?](https://stackoverflow.com/a/60451071/2253682) on StackOverflow*

#### Strikethrough

- `~~Strike this out~~`
- `<s>Strike this out</s>`
- ~~Strike this out~~
- *See [Does Markdown have a way to express strikeout?](https://meta.stackexchange.com/questions/63768/does-markdown-have-a-way-to-express-strikeout/63769#63769) on StackOverflow*

#### Highlight

- [How to add text highlight in markdown example](https://www.w3schools.io/file/markdown-text-highlight/) *by W3Schools*

#### Subscript

- `$CO_2$`
- `CO<sub>2</sub>_`
- $CO_2$

#### Superscript

- `$MC^2$`
- `MC<sup>2</sup>`
- $MC^2$

#### Escape characters

- Use a backslash: `\`
- *See [Basic Syntax > Characters You Can Escape](https://www.markdownguide.org/basic-syntax#characters-you-can-escape) by markdownguide.org*

#### Comments

- [Handbook Markdown Guide > Comments](https://about.gitlab.com/handbook/markdown-guide/#comments) *by GitLab*

# Links

#### Organize links

- Wrap link text: `(some link text)[1]`
    - Provide link at the bottom of the page: `[1]: [www.somelinktext.com](http://www.somelinktext.com)`

#### Email

- `mailto:someemail@domain.xyz`
    * Do not include prefix `https://`

#### Open in a new tab

- `<a href="https://duckduckgo.com" target="_blank">Duck Duck Go</a>`

# Tables

#### Use HTML table builders for complex tables

- Markdown formatting that doesn't work in tables: Headings, lists, line breaks,  images, horizontal rules, and blockquotes.
- UI to build a table
    - [tablesgenerator.com](https://www.tablesgenerator.com/markdown_tables)
        - Build complex tables in HTML to copy and paste into Markdown files.
        - E.g. Text fonts, sizing, lists, and etc.
        - Save and load tables
        - Opportunity
            - Indent text within cells: [Indenting Paragraphs in HTML — All You Need to Know](https://html-tuts.com/indenting-paragraphs-in-html/) _by html-tuts.com_
    - [HackMD](https://hackmd.io/@openinfo/hackmd/https%3A%2F%2Fhackmd.io%2F%40openinfo%2Fhackmd-about-and-features#Web-app)
- Convert CSV and other delimited data into a Markdown table
    - [tableconvert.com](https://tableconvert.com/)
    - [markdown Table Maker](https://jakebathman.github.io/Markdown-Table-Generator/) *by Jake Bathman*

#### Center a table

- [Markdown Center a Text, Image, Title, or Table](https://markdown.land/markdown-center) *by Markdown Land*

#### Resources

- markdownguide.org
    - [Extended Syntax > Tables](https://www.markdownguide.org/extended-syntax/#tables)
    - [Hacks > Table Formatting](https://www.markdownguide.org/hacks/#table-formatting)
- markdown.land
    - [How to Create a Great Looking Table](https://markdown.land/markdown-table)
    - [SQLite Markdown: Format Query Results In Markdown](https://markdown.land/sqlite-markdown)

# Style and theme

- Use *style* tags to implement CSS in a `.md` file.
- Define HTML elements to customize inside the tags.
- [HTML style tag](https://www.w3schools.com/TAGs/tag_style.asp) *by W3Schools*
- [HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) *by Mozilla*

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>