# quarto.test.book

A scratch Quarto book for debugging Quarto problems.
It is not a template and not a course site: nothing depends on it, and nothing is published from it.

Use it, or a branch of it, to reproduce a Quarto problem in a small project before changing a real site
([Morrison-Lab/ai-config#4274](https://github.com/Morrison-Lab/ai-config/issues/4274)).
Its sibling for websites is [`test.quarto.website`](https://github.com/Morrison-Lab/test.quarto.website).

## What is here

- A book with three chapters (`index.qmd`, `intro.qmd`, `summary.qmd`) and a references page.
- Two profiles, `book` and `revealjs` (`_quarto-book.yml`, `_quarto-revealjs.yml`), for trying a book whose chapters also render as slides.
  `_quarto.yml` makes `book` the default.

## Working here

- Put each experiment on its own branch, named for what it tests.
- Say what the branch showed, in its pull request or in an issue, before leaving it.
  The earlier branches (`both-work`, `intro-slides-work`, `intro-slides-dont-work` and others) recorded no result,
  and [#6](https://github.com/Morrison-Lab/quarto.test.book/issues/6) tracks recovering what they showed.
- `_quarto-book.yml` began as a copy of another site's configuration.
  Change its analytics and repository settings before publishing anything from here.
