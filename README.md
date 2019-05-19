<img src="assets/icon.png?raw=true" alt="Hypest Icon" width="148" height="148" />

# Hypest for Hyper
A beautiful and minimal macOS theme for Hyper -- with vibrancy, light and dark
modes, and theming for several popular Hyper plugins.

<img src="assets/preview.jpg?raw=true" alt="Hypest Screenshot" width="600" height="400" />

### Installation

#### From Hyper
`hyper i hyper-hypest`

#### Manually
1. Open `~/.hyper.js` in your text editor
2. Add `hyper-hypest` to the `plugins` array

### Configuration
There are two options that can be passed as optional configuration to change the
theme. To pass the options you can add a `hypest` object to the `config` in
`~/.hyper.js`.

**Note:** you may need to restart Hyper when switching between themes.

#### Dark Mode
Set `darkmode` to true to use the dark version of the theme.
```js

config: {
    ...
    hypest: {
        // Default is false
        darkmode: true
    }
    ...
}
```
<img src="assets/preview-dark.jpg?raw=true" alt="Hypest Screenshot" width="600" height="400" />

#### Vibrancy
Set `vibrancy` to false to disable the window vibrancy effect in either theme.
```js

config: {
    ...
    hypest: {
        // Default is true
        vibrancy: false
    }
    ...
}
```
<img src="assets/preview-no-vibrancy.jpg?raw=true" alt="Hypest Screenshot" width="600" height="400" />

### Plugin support
Hypest includes custom theming to support a few of the most popular Hyper
plugins, including:

- hyper-search
- hyper-statusline
- hyper-tab-icons
- hyper-highlight-active-pane

<img src="assets/preview-with-plugins.jpg?raw=true" alt="Hypest Screenshot" width="600" height="400" />

### Known issues
Any plugins that customize tabs beyond the plugins mentioned above may have
compatibility issues with the theming in Hypest.

At this time Hypest doesn't support user defined colors but it's planned. I'd
also gladly accept [pull requests](https://github.com/dizzyup/hyper-hypest/pulls)
to add that functionality, or to extend allow additional configuration options.