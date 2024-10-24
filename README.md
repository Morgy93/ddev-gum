<div align="center">
    <a href="https://ddev.com/">
        <img src="https://raw.githubusercontent.com/ddev/ddev/master/images/ddev-logo.svg" alt="DDEV logo" height="80">
    </a>
    <a href="https://github.com/charmbracelet/gum">
        <img src="https://stuff.charm.sh/gum/gum.png" alt="gum Logo" height="80">
    </a>
    <h1 align="center">ddev-gum</h1>
</div>

[![tests](https://github.com/Morgy93/ddev-gum/actions/workflows/tests.yml/badge.svg)](https://github.com/Morgy93/ddev-gum/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

## What is Gum?

> A tool for glamorous shell scripts. Leverage the power of [Bubbles](https://github.com/charmbracelet/bubbles) and [Lip Gloss](https://github.com/charmbracelet/lipgloss) in your scripts and aliases without writing any Go code!
>
> ![gum](https://github.com/Morgy93/ddev-gum/assets/7961978/426f48a5-f02e-423e-a894-ca54bd2cd0d1)

For more information, see the [official repository](https://github.com/charmbracelet/gum) or visit <https://charm.sh/>.

YouTube: [Let's build a conventional commit helper script with Gum!](https://youtube.com/watch?v=vtCwt-4tIto)

YouTube Shorts: [Gum: Write Glamorous Shell Scripts](https://www.youtube.com/watch?v=J7S-qastsqg)

## Installation

For DDEV v1.23.5 or above run

```shell
ddev add-on get orgy93/ddev-gum
```

For earlier versions of DDEV run

```shell
ddev get orgy93/ddev-gum
```

Then restart the project

```shell
ddev restart
```

## Usage

### Host shell

```shell
ddev gum
```

### Inside DDEV web commands

```shell
gum
```

Please refer to the documentation at <https://github.com/charmbracelet/gum#interaction>.
