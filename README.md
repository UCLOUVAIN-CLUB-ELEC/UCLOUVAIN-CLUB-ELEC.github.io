# UCLOUVAIN-CLUB-ELEC.github.io

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/UCLOUVAIN-CLUB-ELEC/UCLOUVAIN-CLUB-ELEC.github.io/main.svg)](https://results.pre-commit.ci/latest/github/UCLOUVAIN-CLUB-ELEC/UCLOUVAIN-CLUB-ELEC.github.io/main)

### Contributing

#### Without installing anything

You can contribute to our website and see you changes without having to install **anything**!
This can be done in a thwo-steps process:
  1. [Fork](https://github.com/UCLOUVAIN-CLUB-ELEC/UCLOUVAIN-CLUB-ELEC.github.io/fork) this repository
  2. Follow the [GitHub Pages setup](#github-pages-setup)

You should now be able to access your version of our website at `https://<your_username>.github.io/UCLOUVAIN-CLUB-ELEC.github.io/`. Any change that your will do to your fork (on the chosen branch) will directly reflect in changes your version of the website.

#### With local installation

To properly setup your local environment, please read [this](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll), but **skip** the `jekyll new` command. Then, you can read more about how this theme works [here](https://github.com/chrisrhymes/bulma-clean-theme/blob/master/README.md#usage) or learn with examples by directly looking at the [code](https://github.com/chrisrhymes/bulma-clean-theme) that generates [this website](http://www.csrhymes.com/bulma-clean-theme/).


#### Merging your changes onto our website

Once you are happy with your changes, create a [Pull Request](https://github.com/UCLOUVAIN-CLUB-ELEC/UCLOUVAIN-CLUB-ELEC.github.io/pulls) so that we can review, and hopefully accept your code.

#### GitHub Pages setup

In order to have your version of the website published on GitHub pages, please follow this:
  1. Modify the following entries in `_config.yaml`:
``` yaml
baseurl: "/UCLOUVAIN-CLUB-ELEC.github.io" # the subpath of your site, e.g. /blog
github_username: <your_username>
```
  2. Go to your fork (`https://github.com/<your_username>/UCLOUVAIN-CLUB-ELEC.github.io/`) and go to *Settings* -> *Pages*
  3. In *Source*, select a branch (usually `main`), and press *Save*


You will need to change a few things
