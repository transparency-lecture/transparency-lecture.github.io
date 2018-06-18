---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started

This website is generated using a static website generator called [Jekyll](https://jekyllrb.com/).

It makes it easy for us to focus only on the **content**, not on the layout. This page for example is written
in the intuitive ([markdown](https://en.wikipedia.org/wiki/Markdown)) format,
which you might recognize if you used a Jupyter Notebook before.

To see the source code for this page, visit our
[github repository](https://github.com/transparency-lecture/transparency-lecture.github.io/blob/master/_docs/index.md).
No big deal, right? Here are some tips to get you started.

## Writing new content

### Example

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` (or a subfolder) and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.
