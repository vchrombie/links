# URL Shortener

Inspired from [nelsontky/gh-pages-url-shortener](https://github.com/nelsontky/gh-pages-url-shortener).

## Workflow

1. Create a new issue with the URL you want to shorten as the title.
2. The issue will be automatically closed, and a comment will be added with the shortened URL, by the GitHub Actions.
3. The shortened URL will be redirected to the 404 page.
4. JS will redirect to the original URL which is fetched from the GitHub Issues API.
5. If the URL is not valid, the shortened URL will redirect to the index page.

## Example

[vchrombie.github.io/links/1](https://vchrombie.github.io/links/1)
