<a href="https://github.com/casajaso"><img src="hhttps://avatars2.githubusercontent.com/u/44911805?s=400&u=c53584df8bf9c1f3dab3c97e48d97ae3ed55cf6f&v=4" title="Jason Casas" alt="Jason Casas"></a>

<!-- [![Jason Casas](hhttps://avatars2.githubusercontent.com/u/44911805?s=400&u=c53584df8bf9c1f3dab3c97e48d97ae3ed55cf6f&v=4)](https://github.com/casajaso) -->

***INSERT GRAPHIC HERE (include hyperlink in image)***

# run_command

> Run command(s) on remote host over SSH connection

**Badges will go here**

- build status
- issues (waffle.io maybe)
- devDependencies
- npm package
- coverage
- slack
- downloads
- gitter chat
- license
- etc.

[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger) [![Dependency Status](http://img.shields.io/gemnasium/badges/badgerbadgerbadger.svg?style=flat-square)](https://gemnasium.com/badges/badgerbadgerbadger) [![Coverage Status](http://img.shields.io/coveralls/badges/badgerbadgerbadger.svg?style=flat-square)](https://coveralls.io/r/badges/badgerbadgerbadger) [![Code Climate](http://img.shields.io/codeclimate/github/badges/badgerbadgerbadger.svg?style=flat-square)](https://codeclimate.com/github/badges/badgerbadgerbadger) [![Github Issues](http://githubbadges.herokuapp.com/badges/badgerbadgerbadger/issues.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger/issues) [![Pending Pull-Requests](http://githubbadges.herokuapp.com/badges/badgerbadgerbadger/pulls.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger/pulls) [![Gem Version](http://img.shields.io/gem/v/badgerbadgerbadger.svg?style=flat-square)](https://rubygems.org/gems/badgerbadgerbadger) [![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org) [![Badges](http://img.shields.io/:badges-9/9-ff6799.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger)

---

## Table of Contents

> Click Link to "jump" to section

- [Installation](#installation)
- [Features](#features)
- [Contributing](#contributing)
- [Contributers](#contributers)
- [FAQ](#faq)
- [Support](#support)
- [License](#license)


---

## Example (Optional)

```shell
$ run_command.py -c 'uname -a' 'whoami' 'date' -u jason -i .ssh/access.pem sshserver001
```

---

## Installation

### Clone

- Clone this repo to your local machine via https or ssh

> HTTPS:

```shell
$ git clone https://github.com/casajaso/run_command.git
```

> SSH:

```shell
$ git clone git@github.com:casajaso/run_command.git
```

### Setup

- Prerequisites:

> install and configure prereqs

```shell
$ install prereq
$ config prereq 
```

> Install run_command

```shell
$ cd run_command 
$ pip install run_command
```

---

## Features

### Supports multiple authentication methods:

- interactive password
- private keys stored in ssh_agent
- private keys stored on file-system

## Usage 

```shell
usage: run_command.py [-h] -c COMMAND [COMMAND ...] [-b [BASTIAN]]
                    [-u [USERNAME]] [-i [IDENTITYFILE]] [-p]
                    [hostname]

run commands on remote host over ssh

positional arguments:
  hostname              target hostname or ip (***required)

optional arguments:
  -h, --help            show this help message and exit
  -c COMMAND [COMMAND ...], --command COMMAND [COMMAND ...]
                        command(s) to execute on target host (***required)
                        example: -c 'command' '...' OR -c 'command; ...'
  -b [BASTIAN], --bastian [BASTIAN]
                        proxy through a bastion/jumpbox (default: None)
  -u [USERNAME], --username [USERNAME]
                        username on target host (default: e41p)
  -i [IDENTITYFILE], --identityfile [IDENTITYFILE]
                        use ssh identify file; opens prompt (default: None)
  -p, --password        use password; opens prompt (default: no flag set)

```

## Testsing

---

## Contributing

### To contribute to the project...

> Fork or Clone this Repo

- Fork or Clone this repo: `https://github.com/casajaso/run_command.git`

> Hack Away!

- edit/update/add/remove/***break :P***/fix

> Create a pull request

- Create a new pull request at: <a href="https://github.com/casajaso/run_command/compare/" target="_blank">`https://github.com/casajaso/run_command/compare/`</a>.

---

## Contributers

[contributors]: https://github.com/casajaso/run_command/contributors

---

## FAQ

- None (yet...)

## Support

Reach out to me at one of the following places!

- Github: <a href="https://github.com/casajaso" target="_blank">`Jason Casas`</a>
- Email: <a href="mailto:arkaydez@gmail.com">arkaydez@gmail.com</a>

---

## Donations (Optional)

[![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://www.paypal.me/JasonCasas/)


---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2019 © <a href="https://github.com/casajaso" target="_blank">Jason Casas</a>.
