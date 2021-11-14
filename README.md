# Gh-Cms

> Headless CMS using Github Issues and Github Actions.

## How?
Each time a new issue is created, a new post entry is created.

## Bonus feature
Serve your content before publish it using ngrok. Take a look at `.github/workflows/gh-serve.yml`

## Tech

- Hugo
- Github Actions

## Github actions

- actions/checkout@v2
- peaceiris/actions-hugo@v2
- stefanzweifel/git-auto-commit-action@v4
- oscarnevarezleal/ngrok-tunneling-action@dev
