# formstreak: MaterialFox
A Material Design 2-inspired userChrome.css theme for Firefox. This is a fork of the awesome [Materialfox](https://github.com/muckSponge/MaterialFox/) theme by [@muckSponge](https://github.com/muckSponge) with some additional customizations.

![Light](./light.png)

![Dark](./dark.png)

## Installation

Some steps involve accessing the about:config page. You can get there by typing it into your urlbar.

### Mandatory steps
1. Copy the chrome folder into your Firefox profile directory. To find your profile directory, go to about:support. Alternatively, you can symlink your chrome folder instead of copying.
2. [about:config] Set ```svg.context-properties.content.enabled``` to ```true``` (default is ```false```).
3. Restart Firefox.

### Optional steps
Replicate Chrome's light color scheme:
* Right click on toolbar -> Customize.
* Click Themes.
* Select Light theme.

Add space above tab bar:
* Right click on toolbar -> Customize.
* Check Drag Space checkbox.

Replicate Chrome behaviour for clipped tabs:
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```144```).

Allow tabs to shrink more; tabs in overflow will look the same as pinned tabs:
* [about:config] Add new entry ```materialFox.reduceTabOverflow``` with value ```true```.

Replicate Chrome identity colours (or lack thereof):
* [about:config] Add new entry ```materialFox.disableIdentityColors``` with value ```true```.
* Restart Firefox.

Remove pocket button from Address Bar:
* Right click on pocket button -> Remove from Address Bar

## Note
* Linux is not frequently tested; last tested on 07/09/2018.
* Some customisation settings may no longer work (compact density, some custom themes).