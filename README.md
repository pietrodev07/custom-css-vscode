# Custom CSS for VSCode

## Installation

1. Open VSCode and go to `File > Preferences > Settings`.

2. In the `Extensions` tab, search for `Custom CSS and JS Loader`.

3. Click on the `Install` button.

4. Click on the `Reload` button.

5. Open the settings file by clicking on the `Open Settings (JSON)` button.

6. Paste the following content into the file:

```json
{
  "vscode_custom_css.imports": [
    "file:///Users/<username>/Documents/custom-vscode.css"
  ]
}
```

7. Save the file.

8. Open the `Command Palette` by pressing `Ctrl+Shift+P` or `Cmd+Shift+P`.

9. Type `Reload Custom CSS and JS` and press `Enter`.

## Customization

You can customize the CSS by editing the `custom-vscode.css` file.

## Profile Link

https://vscode.dev/editor/profile/github/cdb8f61f91cefb7cdfc3872c055d0c8e
