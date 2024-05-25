# Alacritty Theme Switcher

A quick theme switcher for [Alacritty](https://github.com/alacritty/alacritty).

## Usage

The theme switcher will generate a `.toml` file containing a single import of the actual theme file.
By default, this file will be located at `$HOME/.config/alacritty/theme.toml`, but can be customized via the `-config_file` command line option.

To use the theme switcher, simply import this theme switcher file in your main `alacritty.toml` config file:

```toml
# ...

import = [
    # ...
    "~/.config/alacritty/theme.toml",
]
# ...
```

Then, run `alacritty-theme-switcher -theme /path/to/chosen/theme.toml`.

To see all options, run `alacritty-theme-switcher -help`.
