Language:
[English](https://pandagix.github.io/index)
[中文](https://pandagix.github.io/index_zh)
[Deutsch](https://pandagix.github.io/index_de)
[日本語](https://pandagix.github.io/index_jp)

## Overview

PandaGix is a [Guix](https://guix.gnu.org/en) based Linux distro.

## Download

[ISO releases](https://github.com/PandaGix/PandaGixISO/releases) that can be used to make a bootable USB-stick

## Installation

Currently with the [Live-ISO](https://git.nju.edu.cn/nju/pandagix-test/-/jobs/5933/artifacts/file/PandaGix-5.4.98z-c317k45x6kr02jdjjjvnz1fb5s5qlqr6-image.iso)
is only manual installation possible.

For installation on native disk, read [Manual Installation](https://guix.gnu.org/manual/en/html_node/Manual-Installation.html#Manual-Installation) 
from the official [GNU Guix Reference Manual](https://guix.gnu.org/manual/en/html_node/index.html).

The template file for operating system config will soon be available on this site after finishing writing this site.

## License

Unless otherwise noted, all files in this distribution are released
under the [GNU GENERAL PUBLIC LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html) (GPLv3).
Exceptions are noted within the associated source files.

## Attention!

This distro do contains non-free software but does NOT endorse any non-free software.
We believe non-free software is non-ethical, harmful to software development and restricts the users' freedom.
See the [GNU philosophy](https://www.gnu.org/philosophy/philosophy.en.html) 
and [What is free software?](https://www.gnu.org/philosophy/free-sw.en.html) for a more thorough discussion.

Those non-free softwares/packages are provided as a last resort, should none of the official Guix packages work for you.

You should understand the implication of using non-free software. Some of those implications include:
- Endorsement of non-free products and the perpetration of a culture of restriction on liberties.
- Non-free software cannot (or hardly) be audited: it can potentially spy on you, destroy or steal your data.

As a minimal security measure, runing non-free software inside a container is recommended.

## Contact

Bug reports may go to [Issues](https://github.com/PandaGix/pandagix.github.io/issues).

Ideas and advices are welcome at [Discussions](https://github.com/PandaGix/pandagix.github.io/discussions).

XMPP [chat room](https://blabber.im/en/j/pandagixusers@conference.blabber.im) URL or URI xmpp:pandagixusers@conference.blabber.im

## Contribution

Help make this site better through [PR](https://github.com/PandaGix/pandagix.github.io/pulls). 

Help with **Goals** below by contacting us through the mentioned methods.

## Goals

- [x] A bootable Live-ISO
- [ ] Artworks (logo, wallpaper, etc.)
- [x] Auto-build with GitLab's CI/CD for the Live-ISO 
- [ ] Laptop and tablet compatible on x86_64 (WiFi, Bluetooth, touchpad, touchscreen, etc.)
- [ ] Disk installation to removable disk
- [ ] A graphical guided installer that runs in the Live-ISO
- [ ] Coustom _channel_ with useful apps [ChnGix](https://git.nju.edu.cn/nju/chngix)
- [ ] Internationalization (some GNOME components, prefer contributions to upstream Guix)
