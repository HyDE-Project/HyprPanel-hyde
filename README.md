# HyprPanel wallbash template

### Wallbash Template for HyprPanel

This template is designed for use with HyprPanel. For more information, visit [HyprPanel](https://hyprpanel.com/).

> **NOTE:** This is not a standalone package. Ensure you have HyDe installed and a working HyprPanel setup.

## Usage

Add the file `/hyprpanel.dcol` to either `~/.config/hyde/wallbash/Wall-Ways` or `~/.config/hyde/wallbash/Wall-Dcol`.

### Difference Between Wall-Ways and Wall-Dcol

- **Wall-Ways**: This file is always used regardless of the theme mode or wallbash mode.
- **Wall-Dcol**: This file attempts to find the theme template (if in theme mode) and falls back to using the dominant color of the wallpapers if no template is available.

### Using This Template for Themes

1. **Header Line**:
    ```sh
    ${cacheDir}/landing/hyprpanel_wallbash.json | ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"
    ```
    This command sets the theme using the cached wallbash-generated `.json` file.
    `$cacheDir` is the path to `~/.cache/hyde/`.

2. **Wallbash Generation**:
    ```sh
    ${cacheDir}/landing/hyprpanel_wallbash.json
    ```
    This command generates the wallbash `.json` file.

3. **Optional Command**:
    ```sh
    ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"
    ```
    This command uses the cached wallbash-generated `.json` file to set the theme.

## TODO
- Dedicated installation

## Contributions

- Enhance the template by adding more contrast to some elements.
- Avoid making breaking changes.
- Make readme comprehensive
- Feel free to open a PR for color corrections!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A)
