# README

## How to update docs:
1. Edit Jekyll templates in `/docs`
2. Run `$ be jekyll serve` in `/docs` directory
3. View the site at `http://localhost:4000`

Refer to https://jekyllrb.com/ & https://github.com/jekyll/jekyll for more info

## How to update GraphQL API docs:
1. Run `$ graphdoc -e http://localhost:3000/graphql -o ./docs/schema`
2. Run `$ be jekyll serve` in `/docs` directory
3. View the generated GraphQL API docs at `http://localhost:4000/schema`

Refer to https://2fd.github.io/graphdoc/ & https://github.com/2fd/graphdoc for more info