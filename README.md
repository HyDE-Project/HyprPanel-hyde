# hyprpanel wallbash template
# Wallbash Template for HyprPanel

This template is designed for HyprPanel. For more information, visit [HyprPanel](https://hyprpanel.com/).

> **NOTE:** This is not a standalone package. Ensure you have HyDe installed and a working HyprPanel setup.

## Usage

Add the file `/hyprpanel.dcol` to either `~/.config/hyde/wallbash/Wall-Ways` or `~/.config/hyde/wallbash/Wall-Dcol`.

### Difference Between Wall-Ways and Wall-Dcol

- **Wall-Ways**: Always used regardless of theme mode or wallbash mode.
- **Wall-Dcol**: Attempts to find the theme template (if in theme mode) and falls back to using the dominant color of the wallpapers if no template is available.

### Using This Template for Themes

1. **Header Line**: 
    ```sh
    ${cacheDir}/landing/hyprpanel_wallbash.json | ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"
    ```
2. **Wallbash Generation**: 
    ```sh
    ${cacheDir}/landing/hyprpanel_wallbash.json
    ```
3. **Optional Command**: 
    ```sh
    ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"
    ```
    This command uses the cached wallbash-generated `.json` file.

## Contributions

- Enhance the template by adding more contrast to some elements.
- Avoid breaking changes.
- Feel free to open a PR for color corrections!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A3TECUZ)
