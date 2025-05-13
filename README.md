# puppet-zsh

[![Build Status](https://img.shields.io/github/actions/workflow/status/opus-codium/puppet-zsh/release.yml)](https://github.com/opus-codium/puppet-zsh/releases)
[![Puppet Forge](https://img.shields.io/puppetforge/v/opuscodium/zsh.svg)](https://forge.puppetlabs.com/opuscodium/zsh)
[![Puppet Forge - downloads](https://img.shields.io/puppetforge/dt/opuscodium/zsh.svg)](https://forge.puppetlabs.com/opuscodium/zsh)
[![Puppet Forge - endorsement](https://img.shields.io/puppetforge/e/opuscodium/zsh.svg)](https://forge.puppetlabs.com/opuscodium/zsh)
[![Puppet Forge - scores](https://img.shields.io/puppetforge/f/opuscodium/zsh.svg)](https://forge.puppetlabs.com/opuscodium/zsh)
[![License](https://img.shields.io/github/license/opus-codium/puppet-zsh.svg)](https://github.com/voxpupuli/opuscodium-zsh/blob/master/LICENSE.md)

#### Table of Contents

<!-- vim-markdown-toc GFM -->

* [Module description](#module-description)
* [Usage](#usage)

<!-- vim-markdown-toc -->

## Module description

The zsh module takes care of installing zsh on various platforms.

## Usage

All that's needed to use this module is to add the line below to a profile for
the host on which you want to use zsh:

```puppet
include zsh
```
