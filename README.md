# BETA - Home Assistant Add-on Repository for Matthias Balkes Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## WARNING! THIS IS A BETA REPOSITORY

This Home Assistant Add-ons repository contains beta releases of add-ons.

- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.

If you are more interested in stable releases of our add-ons:

<https://github.com/matthiasbalke/ha-addons>

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this repository is to provide an add-on to use Collabora CODE.
Additional add-ons might follow in the future.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/matthiasbalke/ha-addons-beta
```

## Add-ons provided by this repository

### &#10003; [Collabora Online Development Edition (CODE)][addon-collabora-code]

![Latest Version][collabora-code-version-shield]
![Supports armhf Architecture][collabora-code-armhf-shield]
![Supports armv7 Architecture][collabora-code-armv7-shield]
![Supports aarch64 Architecture][collabora-code-aarch64-shield]
![Supports amd64 Architecture][collabora-code-amd64-shield]
![Supports i386 Architecture][collabora-code-i386-shield]

Collabora Online Development Edition - an awesome, Online Office suite image suitable for home use.

[:books: Collabora Online Development Edition (CODE) add-on documentation][addon-doc-collabora-code]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

The beta add-ons will also have an additional beta marker, unless, the
stable release is newer, in that case, the stable release is published
in this channel.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Collabora Online Development Edition (CODE)][collabora-code-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

# MIT License

Copyright (c) 2025 Matthias Balke

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

[addon-collabora-code]: https://github.com/matthiasbalke/addon-collabora-code/tree/v0.2.0
[addon-doc-collabora-code]: https://github.com/matthiasbalke/addon-collabora-code/blob/v0.2.0/README.md
[collabora-code-issue]: https://github.com/matthiasbalke/addon-collabora-code/issues
[collabora-code-version-shield]: https://img.shields.io/badge/version-v0.2.0-blue.svg
[collabora-code-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[collabora-code-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[collabora-code-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[collabora-code-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[collabora-code-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/u/matthiasbalke
[issue]: https://github.com/matthiasbalke/ha-addons-beta/issues
[license-shield]: https://img.shields.io/github/license/matthiasbalke/ha-addons-beta.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-development-yellowgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html