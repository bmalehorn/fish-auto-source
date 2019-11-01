# Auto Source

Never type `source ~/.config/fish/config.fish` again.

`auto-source` will automatically source `~/.config/fish/config.fish` if it's been modified since the last command.

## Installation

### `fisher`

```
fisher add bmalehorn/fish-auto-source
```

### Manual

Copy/paste the contents of [fish_auto_source.fish](./conf.d/fish_auto_source.fish) into your `config.fish`.

## Credits

This function was originally written by [@c02y](https://github.com/c02y) in [this post](https://github.com/fish-shell/fish-shell/issues/5707). I just packaged it and handled a few edge cases.
