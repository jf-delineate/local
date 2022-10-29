[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <img alt="delineate.io" src="https://github.com/delineateio/.github/blob/master/assets/logo.png?raw=true" height="75" />
  <h2 align="center">delineate.io</h2>
  <p align="center">portray or describe (something) precisely.</p>

  <h3 align="center">Brewfile</h3>

  <p align="center">
    Source controlled Brewfile to re-create local environments.
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

The purpose of this project to have a well managed list of locally [brew](https://brew.sh/) installed programs.

The `HOMEBREW_BUNDLE_FILE` env variable should be set to point to the cloned directory, then the following commands can be used

```shell
# Uninstalls any brew installs not in the Brewfile
brew bundle cleanup --force

# Installs or upgrades any brew installs in the Brewfile
brew bundle install --force
```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best README Template](https://github.com/othneildrew/Best-README-Template)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[forks-shield]: https://img.shields.io/github/forks/delineateio/oss-template.svg?style=for-the-badge&logo=github
[forks-url]: https://github.com/delineateio/oss-template/network/members
[stars-shield]: https://img.shields.io/github/stars/delineateio/oss-template.svg?style=for-the-badge&logo=github
[stars-url]: https://github.com/delineateio/oss-template/stargazers
[license-shield]: https://img.shields.io/github/license/delineateio/oss-template.svg?style=for-the-badge&logo=github
[license-url]: https://github.com/delineateio/oss-template/blob/master/LICENSE
