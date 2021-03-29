<!--
*** We're using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stars][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

# Start Your Lab Workshop

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/startyourlab/workshop">
    <img src="assets/images/logo.png" alt="Logo" height="80">
  </a>

  <h3 align="center">Start Your Lab Workshop</h3>

  <p align="center">
    A workshop for labs learning how to get started with best practices and digital collaboration tools.
    <br />
    <a href="https://github.com/startyourlab/workshop/issues">Report Bug</a>
    ·
    <a href="https://github.com/startyourlab/workshop/issues">Request Feature</a>
  </p>
</p>

## About The Project

The Start Your Lab Workshop is part of an open-source initiative to teach academic research
labs how to leverage modern tools and support them with industry best practices.

### Built With

* [RStudio](https://www.rstudio.com/)
* [xaringan](https://github.com/yihui/xaringan)
* [pagedown]()

### Installation

To contribute to this project, be sure R and RStudio are up to date on your computer.
Then, clone this repository into your local projects directory and navigate into the
project root:

```sh
git clone https://github.com/startyourlab/workshop
cd workshop
```

Then, open the project in RStudio. When in RStudio, if `xaringan` is not already
installed, run

```r
remotes::install_github('yihui/xaringan')
```

in the R Console. Once installed, load the package via `library(xaringan)`.
To test that everything works, open the `slides.Rmd` file and use the **Knit**
button in the top left of the RStudio window.

### Export to PDF

With the `pagedown` package and Google Chrome, the function `pagedown::chrome_print()`
can export a PDF of the HTML created from the `slides.Rmd` file. To install via the
R Console, run

```r
install.packages('pagedown')
```

then with the project root directory as the working directory, run

```r
pagedown::chrome_print('slides.Rmd')
```

## Code of Conduct

Start Your Lab is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/startyourlab/.github/tree/main/CODE_OF_CONDUCT.md) for our GitHub organization.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.


<!-- CONTACT -->
## Contact

Start Your Lab - [@startyourlab](https://twitter.com/startyourlab) - ari@startyourlab.com

Project Link: [https://github.com/startyourlab/workshop](https://github.com/startyourlab/workshop)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

...

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/startyourlab/workshop?style=for-the-badge
[contributors-url]: https://github.com/startyourlab/workshop/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/startyourlab/workshop?style=for-the-badge
[forks-url]: https://github.com/staryourlab/workshop/network/members
[stars-shield]: https://img.shields.io/github/stars/startyourlab/workshop?style=for-the-badge
[stars-url]: https://github.com/staryourlab/workshop/stargazers
[issues-shield]: https://img.shields.io/github/issues/startyourlab/workshop?style=for-the-badge
[issues-url]: https://github.com/staryourlab/workshop/issues
[license-shield]: https://img.shields.io/github/license/startyourlab/workshop?style=for-the-badge
[license-url]: https://github.com/staryourlab/workshop/blob/master/LICENSE.md
[product-screenshot]: assets/images/product-screenshot.png
