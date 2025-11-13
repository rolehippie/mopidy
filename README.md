# mopidy

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/mopidy)
[![General Workflow](https://github.com/rolehippie/mopidy/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/mopidy/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/mopidy/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/mopidy/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/mopidy/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/mopidy/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/mopidy)](https://github.com/rolehippie/mopidy/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.mopidy-blue)](https://galaxy.ansible.com/rolehippie/mopidy)

Ansible role to install mopidy music player.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [mopidy_distro](#mopidy_distro)
  - [mopidy_extra_packages](#mopidy_extra_packages)
  - [mopidy_general_packages](#mopidy_general_packages)
  - [mopidy_keyring](#mopidy_keyring)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### mopidy_distro

Distribution used for repository

#### Default value

```YAML
mopidy_distro: bullseye
```

### mopidy_extra_packages

List of extra packages to install

#### Default value

```YAML
mopidy_extra_packages:
  - mopidy-podcast
  - mopidy-somafm
```

### mopidy_general_packages

List of general packages to install

#### Default value

```YAML
mopidy_general_packages:
  - mopidy
  - mopidy-local
  - mopidy-mpd
  - mopidy-mpris
```

### mopidy_keyring

Path for the repository keyring

#### Default value

```YAML
mopidy_keyring: /usr/share/keyrings/mopidy-archive-keyring.gpg
```

## Discovered Tags

**_mopidy_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
