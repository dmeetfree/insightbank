---
slug: get-started
description: This is insightbank first post on Docusaurus.
title: Get started
authors: [dmeetfree]
tags: [blog, start, docusaurus]
image: https://i.imgur.com/mErPwqL.png
hide_table_of_contents: false
---

This is the summary of a get started long blog post,

Use a `<!--` `truncate` `-->` comment to limit blog post size in the list view.

<!--truncate-->

[Docusaurus blogging features](https://docusaurus.io/docs/blog) are powered by the [blog plugin](https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-blog).

Simply add Markdown files (or folders) to the `blog` directory.

Regular blog authors can be added to `authors.yml`.

New authors should be added with
```yaml
authors:
  - name: Dmitry Ramanouski
    title: Insightbank Core Team
    url: https://github.com/dmeetfree
    image_url: https://github.com/dmeetfree.png
```

The blog post date can be extracted from filenames, such as:

- `YYYY-MM-DD-my-blog-post-title.md`
- `YYYY-MM-DD-my-blog-post-title/index.md`
- `YYYY/MM/DD/my-blog-post-title.md`

A blog post folder can be convenient to co-locate blog post images:

![Docusaurus Plushie](docusaurus-plushie-banner.jpeg)

The blog supports tags as well!

**And if you don't want a blog**: just delete this directory, and use `blog: false` in your Docusaurus config.
