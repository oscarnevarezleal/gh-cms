# Gh-Cms

> Headless CMS using Hugo, Github Issues and Github Actions.

## How?
Every time a new issue is created, a new post is created as well.

## Branch structure

- _main_ branch holds the content in markdown format. See `content` folder
- _gh-pages_ branch contains the distributable html site.

## Bonus feature
Serve your content before publish it using ngrok.Take a look at `.github/workflows/gh-serve.yml`

## Tech

- Hugo
- Github Actions

## Github actions

- actions/checkout@v2
- peaceiris/actions-hugo@v2
- stefanzweifel/git-auto-commit-action@v4
- oscarnevarezleal/ngrok-tunneling-action@dev
