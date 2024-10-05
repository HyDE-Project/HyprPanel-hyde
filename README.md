# hyprpanel wallbash template
Wallbash template for hyprpanel. See https://hyprpanel.com/

>[! NOTE] This is not a standalone package and be sure to have HyDe installed also be sure to have a working hyprpanel!

# Usage
Add `/hyprpanel.dcol` to ` ~/.config/hyde/wallbash/Wall-Ways` or `~/.config/hyde/wallbash/Wall-Dcol` 
### Difference of Wall-Ways and Wall-Dcol 
* Wall-Ways will always be used no matter what either in theme mode or in wallbash mode.
* Wall-Dcol will try to find the theme template (if it is in theme mode) and fall back to using the Dcol (Dominant color) of the Wallpapers if no template available.

### Use this as templating for themes!

* This is out header line
` ${cacheDir}/landing/hyprpanel_wallbash.json | ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"` 
* wallbash will generate this `  ${cacheDir}/landing/hyprpanel_wallbash.json `
* Then we run an optional command `  ags -r "useTheme('${cacheDir}/landing/hyprpanel_wallbash.json')"` to use the cached wallbash generated .json file.

# Contributions
* You can make this template better by adding more contrast on some elements
* No breaking changes please
* Feel free to open PR for color corrections!
 
 [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A3TECUZ) 
