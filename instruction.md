# Instructions
Setup a few things with Zen.

## Update your settings
### Passwords
- [ ] Ask to save passwords

## Disable Borders
Disable borders by doing the following:
- Open config by typing `about:config` in the address bar.
- Click `Accept the Risk and Continue`.
- Search for `zen.theme.content-element-separation` on the preference name.
- Set it 0.

## Tabs on the right
To move the toolbar to the right, hover over an empty space inside it, right-click, then check `Tabs on the right`.

## Extensions
- [AdGuard AdBlocker](https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker/)
- [Proton Pass](https://addons.mozilla.org/en-US/firefox/addon/proton-pass/)
- [Vimium](https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/)
- [Custom Style Script](https://addons.mozilla.org/en-US/firefox/addon/custom-style-script/)

## Vimium
### Excluded URLs and keys
- `https?://jstris.jezevec10.com/*` — `All`
### Custom key mappings
```
map <C-;> createTab https://jstris.jezevec10.com
```

## Custom Style Script
### URL
- `https://jstris.jezevec10.com/`
### Style (CSS)
```css
#lrem {
  color: white !important;
  margin-top: -380px !important;
  margin-left: -160px !important;
  z-index: 999999 !important;
  position: absolute !important;
  width: 50px !important;
  height: 50px !important;
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
}
#sprintText {
  display: none !important;
}
```
