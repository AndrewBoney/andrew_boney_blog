# Andrew Boney — Personal Projects & Research

Overview
--------

This site hosts my personal side projects, experiments, and research. I use it to document deep dives, working notes, and runnable examples so I can both explore ideas and share findings.

The site is hosted using github pages - [link](https://andrewboney.github.io/andrew_boney_blog/)

Writing with SolveIt
--------------------

I use SolveIt (https://solve.it.com/) to write posts with AI assistance and guidance. The idea came from a deep dive I did with ChatGPT — having a conversational chatbot helped my understanding and shaped the research. Using SolveIt to draft and iterate, then publishing the results in a blog format gives me the ability to run code interactively during deep dives and to keep a reproducible record of findings.

How this repo is organized / used
---------------------------------

- Posts are written as Jupyter notebooks under the `posts/` directory and rendered into the site with Quarto.
- The site is built locally with `quarto preview` and rendered to `_site/` for the published site.
- Deployment is automated via GitHub Actions which publish the site to GitHub Pages.

Install / Requirements
----------------------

Prerequisites:

- Install Quarto: https://quarto.org/
- Install Python 3.8+ and `pip`.

Preview the site locally:

```bash
quarto preview
```

Python Packages required for posts should be installed on a case-by-case basis. 

File structure
--------------

- **_quarto.yml**: Quarto site configuration.
- **index.qmd**: Home page content.
- **about.qmd**: About page content.
- **posts/**: Jupyter notebooks for individual posts (each post is a folder with an index and assets).
- **_site/**: Generated site output (HTML, assets) produced by Quarto.
- **assets/**: Media and static assets used by the site.
- **styles.css**: Custom site styles.

Next steps
----------

- Write new posts as notebooks in `posts/` and preview with `quarto preview`.
- Push changes to GitHub to trigger the GitHub Actions deployment to Pages.