# draculaish-ha-theme
Dracula-Inspired Theme for Home Assistant, Built on the Catppuccin template with extensive changes. 

## Installation
### With [HACS](https://hacs.xyz/)
1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
2. Go to the Community Store.
3. Search for `draculaish`.
4. Navigate to `draculaish` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

## Credits
- [Dracula Theme](https://github.com/dracula)
- [Dracula.min - Dark & Light themes for VS Code](https://github.com/AshGrowem/Dracula.min)
- [Catpuccin Theme for HA](https://github.com/catppuccin/home-assistant) 
