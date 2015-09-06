<div align="center">
  <a href="http://github.com/fish-shell/omf">
  <img width=90px  src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
  </a>
</div>
<br>

> A theme inspired by [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/lambda.zsh-theme)'s [lambda](http://zshthem.es/screenshots/lambda.png) theme.

## Install

```fish
$ omf theme l
```

## Features

* Current branch
* Dirty working directory
* Working directory

## Screenshot

<p align="center">
<img src="http://f.cl.ly/items/2J3M0f2X1j3u471y080I/2.png">
<img src="hhttp://f.cl.ly/items/2S25360U1p360E0D2u2g/3.png">
<img src="http://f.cl.ly/items/1w0s0Q3x3r2Z1F1l011k/4.png">
</p>

## Configuration

Only if fish_theme_l_right_prompt variable is set true within config.fish:
```fish
set theme_display_rbenv 'yes'
set theme_display_rbenv_gemset 'yes'
# if you want to display rbenv ruby version only within directories that contain Gemfile
set theme_display_rbenv_with_gemfile_only 'yes'
```

* Rbenv Ruby Version
* Rbenv Ruby Gemset

<p align="center">
<img src="http://f.cl.ly/items/0f0k3o2L3y2q1L3g1R1X/5.png">
</p>

# License

[MIT][mit] © [bpinto][author] et [al][contributors]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/bpinto
[contributors]:   https://github.com/oh-my-fish/theme-default/graphs/contributors
[omf-link]:       https://www.github.com/fish-shell/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
[travis-badge]:   http://img.shields.io/travis/oh-my-fish/theme-default.svg?style=flat-square
[travis-link]:    https://travis-ci.org/oh-my-fish/theme-default

