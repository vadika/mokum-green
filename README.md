# Mokum Dark Green Mode Firefox Extension

A simple Firefox extension that transforms mokum.place to use a dark background with green text, creating a classic terminal-like appearance.

## Features

- Changes website background to black
- Changes all text to green (#00ff00)
- Makes links a slightly lighter green for better visibility
- Applies dark theme to input fields and text areas
- Overrides default website styles with !important declarations

## Installation Instructions

### Temporary Installation (for testing)

1. Download all extension files
   - Create a new directory for the extension
   - Save `manifest.json` and `style.css` in this directory

2. Open Firefox and enter `about:debugging` in the address bar

3. Click on "This Firefox" in the left sidebar

4. Click "Load Temporary Add-on"

5. Navigate to your extension directory and select the `manifest.json` file

Note: Temporary installations will be removed when Firefox is closed.

### Permanent Installation

1. Zip the extension files
   - Create a ZIP archive containing `manifest.json` and `style.css`
   - Make sure the files are in the root of the ZIP, not in a subdirectory

2. Open Firefox and enter `about:addons` in the address bar

3. Click the gear icon (⚙️) and select "Install Add-on From File"

4. Select your ZIP file

5. Click "Add" when prompted to add the extension

## Customization

You can modify the colors by editing `style.css`:

- To change text color, modify the `color` property values
- Current green: `#00ff00`
- Link color: `#33ff33`
- For a darker green: try `#006600`
- For a lighter green: try `#66ff66`

## Troubleshooting

If the extension doesn't work:

1. Check that it's enabled in `about:addons`
2. Verify the files are properly structured
3. Try refreshing the mokum.place page
4. Check Firefox's console for any error messages

## Permission Notes

This extension only requires permission for mokum.place domains and does not collect any data.

## License

This extension is provided under the MIT License. Feel free to modify and distribute as needed.
