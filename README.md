# kitty-configs

My kitty config files

## Changing Kitty Icon

**Mac:**

Updates Kitty Icon

```sh
kitty +runpy 'from kitty.fast_data_types import cocoa_set_app_icon; import sys; cocoa_set_app_icon(*sys.argv[1:]); print("OK")' ~/.config/kitty/kitty-dark.icns
```

Restarts Mac Dock:

```sh
rm /var/folders/*/*/*/com.apple.dock.iconcache; killall Dock
```

**Linux**:
