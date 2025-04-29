# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/joschi-ha/repository-edge
```

## Add-ons provided by this repository

### &#10003; [CUPS][addon-cups-airprint]

![Latest Version][cups-airprint-version-shield]
![Supports armhf Architecture][cups-airprint-armhf-shield]
![Supports armv7 Architecture][cups-airprint-armv7-shield]
![Supports aarch64 Architecture][cups-airprint-aarch64-shield]
![Supports amd64 Architecture][cups-airprint-amd64-shield]
![Supports i386 Architecture][cups-airprint-i386-shield]

A CUPS print server with working AirPrint

[:books: CUPS add-on documentation][addon-doc-cups-airprint]

### &#10003; [SANE][addon-sane-scanner]

![Latest Version][sane-scanner-version-shield]
![Supports armhf Architecture][sane-scanner-armhf-shield]
![Supports armv7 Architecture][sane-scanner-armv7-shield]
![Supports aarch64 Architecture][sane-scanner-aarch64-shield]
![Supports amd64 Architecture][sane-scanner-amd64-shield]
![Supports i386 Architecture][sane-scanner-i386-shield]

A SANE server for wireless scanning

[:books: SANE add-on documentation][addon-doc-sane-scanner]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant Community Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: CUPS][cups-airprint-issue]
- [Open an issue for the add-on: SANE][sane-scanner-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Adding a new add-on

We are currently not accepting third party add-ons to this repository.

For questions, please contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]
- Message him via the forums: [frenck][forum-frenck]

## License

MIT License

Copyright (c) 2017-2024 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-cups-airprint]: https://github.com/joschi-ha/addon-cups-airprint/tree/8e54119
[addon-doc-cups-airprint]: https://github.com/joschi-ha/addon-cups-airprint/blob/8e54119/README.md
[cups-airprint-issue]: https://github.com/joschi-ha/addon-cups-airprint/issues
[cups-airprint-version-shield]: https://img.shields.io/badge/version-8e54119-blue.svg
[cups-airprint-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[cups-airprint-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[cups-airprint-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[cups-airprint-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[cups-airprint-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-sane-scanner]: https://github.com/joschi-ha/addon-sane/tree/bb9e28a
[addon-doc-sane-scanner]: https://github.com/joschi-ha/addon-sane/blob/bb9e28a/README.md
[sane-scanner-issue]: https://github.com/joschi-ha/addon-sane/issues
[sane-scanner-version-shield]: https://img.shields.io/badge/version-bb9e28a-blue.svg
[sane-scanner-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[sane-scanner-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[sane-scanner-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[sane-scanner-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[sane-scanner-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/joschi-ha/repository-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/joschi-ha/repository-edge/pipelines
[issue]: https://github.com/joschi-ha/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/joschi-ha/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html