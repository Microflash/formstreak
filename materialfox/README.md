# formstreak: MaterialFox
A Material Design 2-inspired userChrome.css theme for Firefox. This is a fork of the awesome [Materialfox](https://github.com/muckSponge/MaterialFox/) theme by [@muckSponge](https://github.com/muckSponge) with some additional customizations.

![Light](./light.png)

![Dark](./dark.png)

## Installation

Some steps involve accessing the about:config page. You can get there by typing it into your urlbar.

### Mandatory instructions
1. Copy the chrome folder into your Firefox profile directory. To find your profile directory, go to about:support. Alternatively, you can symlink your chrome folder instead of copying.
2. [about:config] Set ```svg.context-properties.content.enabled``` to ```true``` (default is ```false```).
3. Restart Firefox.

### Recommended instructions
Disable any existing themes
* Right click on toolbar -> Customize.
* Click Themes.
* Select Light theme.

For better theme/color control:
* Install [MaterialFox Helper](https://addons.mozilla.org/en-US/firefox/addon/materialfox-helper/).
* Click the MaterialFox Helper button and select Light (Material) or Dark (Material) depending on taste.
* Useful on macOS Mojave (dark mode) to force a better looking dark theme.

Add space above tab bar
* Right click on toolbar -> Customize.
* Check Drag Space checkbox.

Emulate Chrome's profile switcher button
* Right click on toolbar -> Customize.
* Drag Synced Tabs to the toolbar.

Replicate Chrome behavior for clipped tabs
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```144```).

Allow tabs to shrink more; tabs in overflow will look the same as pinned tabs
* [about:config] Add new entry ```materialFox.reduceTabOverflow``` with value ```true```.

Replicate Chrome's "Not Secure" on HTTP
* [about:config] Set ```security.insecure_connection_text.enabled``` to ```true```.

## Note
* Linux is not frequently tested; last tested on 11/16/2018.
* Some customisation settings may no longer work (such as compact density).
* Some themes, including built in Light and Dark may clash with address bar.