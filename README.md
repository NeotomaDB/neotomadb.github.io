# Neotoma Open Data Resources

<!-- badges: start -->

[![lifecycle](https://img.shields.io/badge/lifecycle-stable-orange.svg)](https://www.tidyverse.org/lifecycle/#stable)
[![NSF-XXXXXXX](https://img.shields.io/badge/NSF-1948926-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948926)

This page serves as the source of [https://open.neotomadb.org](https://open.neotomadb.org), it powers the GitHub pages releases of the [Neotoma GitHub repositories](https://github.com/NeotomaDB) and provides additional support and resources for users of Neotoma.

<!-- badges: end -->

## Contributors

This project is an open project, and contributions are welcome from any individual.  All contributors to this project are bound by a [code of conduct](CODE_OF_CONDUCT.md).  Please review and follow this code of conduct as part of your contribution.

* [Simon Goring](http://goring.org) [![orcid](https://img.shields.io/badge/orcid-0000--0002--2700--4605-brightgreen.svg)](https://orcid.org/0000-0002-2700-4605)

### Tips for Contributing

Issues and bug reports are always welcome.  Code clean-up, and feature additions can be done either through pull requests to project forks or branches.

All products of the Throughput Annotation Project are licensed under an [MIT License](LICENSE) unless otherwise noted.

## How to use this repository

This repository is run and compiled using [Jekyll](https://jekyllrb.com/). To run Jekyll users need to install Ruby. All instructions for installation and use are described on the [Jekyll Installation pages](https://jekyllrb.com/docs/installation/).

Once Jekyll is installed the site can be run locally using the command:

```bash
jekyll serve
```

This will render the site (by default using port `4000` -- i.e., `http://localhost:4000` on your browser). The site can be built locally using `jekyll build`.

Because `open.neotomadb.org` is connected to the GitHub account as a default URL, all other resources across the [NeotomaDB organization](https://github.com/NeotomaDB) that have GitHub Pages set up can be accessed by replacing `https://github.com/NeotomaDB/` with `https://open.neotomadb.org/`, so, for example, the State of the Database report, which has a GitHub Pages address at `https://github.com/NeotomaDB/NeotomaSummary/StateoftheDB.html` can be accessed at `https://open.neotomadb.org/NeotomaSummary/StateoftheDB/html`.

![Neotoma webpage following a sucessful build.](/images/openneotomapage.png).