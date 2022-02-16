# ANSILambda

The unofficial fork of the [omf][lnk1] [neolambda][lnk2] theme, itself a fork of the [lambda][lnk3] theme. Designed to *only* use ANSI colors rather than hardcoded RGB values. 

[lnk1]: <https://github.com/oh-my-fish/oh-my-fish>
[lnk2]: <https://github.com/ipatch/theme-neolambda>
[lnk3]: <https://github.com/hasanozgan/theme-lambda>

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com)

<a id="featurecast"></a>

> To avoid [double printing](https://raw.githubusercontent.com/ipatch/theme-lambda/master/lib/virtualenv-double-prompt.png) of the virtualenv name in prompt add the below to `config.fish`

```shell
set -gx VIRTUAL_ENV_DISABLE_PROMPT 1
```

<a id="install"></a>

## Install

<a id="install-omf"></a>

### [Oh-My-Fish](https://github.com/oh-my-fish/oh-my-fish)

```shell
omf install https://github.com/danielgleonard/theme-ansilambda.git
```

## TODOs

- [ ] look into creating project based icons, ie. replace `λ` with a green box if inside a node project, ie. if the shell/theme detects a `package.json` file. 
- [ ] experiment with creating an animated svg to replace / complement the animaged gif

  `cat myrecrod.cast | svg-term --out myrecord.svg --window`
