# JoshQuinlan.co.uk

These are the source files for my personal website, built using Hugo and the and the [Bear Cub theme](https://github.com/clente/hugo-bearcub/tree/main).

## Continuous Deployment

This repo uses GitHub Actions to automatically build and deploy any updates made to the `master` branch into production.

It is therefore recommended to push to another branch and then open a PR to verify all of your changes.

## Development

To work on this site, please first make sure that you have Hugo (Extended) installed on your machine, as per [Hugo's Quick Start guide](https://gohugo.io/getting-started/quick-start/).

Once you have Hugo installed and available in your `$PATH`, simply clone down this repo and run `hugo server` to spin up a local web server. Open the link shown in your terminal in your preferred browser, and whenever you write changes the page will auto-update.
