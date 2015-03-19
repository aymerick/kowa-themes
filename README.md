# kowa-themes

All available themes for [kowa](https://github.com/aymerick/kowa), the static website manager.

See <https://github.com/aymerick/kowa> for more informations.


## Get all themes

Clone this repository with `--recursive` flag to checkout all submodules:

    $ git clone --recursive git@github.com:aymerick/kowa-themes.git themes

To update all themes:

    $ git submodule update --remote


## Add a theme

To add a theme to that repository:

    $ git submodule add -b master git@github.com:<repo>/<theme>.git <theme-name>
