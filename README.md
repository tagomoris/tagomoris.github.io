# @tagomoris website

This repository is to host data to generate the personal website of [@tagomoris](https://github.com/tagomoris).
The web page is https://www.tagomor.is/ and hosted by GitHub Pages (through https://tagomoris.github.io/).

## Static site

The site is generated statically by Hugo, designed with hugo-profile, and deployed by GitHub Actions.

See documents:

- [Hugo Quickstart](https://gohugo.io/getting-started/quick-start/)
- [Host on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [Theme hugo-profile](https://github.com/gurusabarish/hugo-profile)

## Configuration

The GitHub Pages is configured to deploy the site from `gh-pages` branch, pushed by GitHub Actions.

And the DNS entry about `https://tagomor.is` is configured on my personal AWS account. See the management console of Route 53.

## Deployments

Commit the content and then push to the `main` branch. Check [Actions](https://github.com/tagomoris/tagomoris.github.io/actions) page to see the deployment tasks.
