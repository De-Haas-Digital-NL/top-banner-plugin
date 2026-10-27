# Bottom Banner Plugin

A banner fixed to the bottom of the viewport. The plugin has no server code: the
CMS fills the `inject` templates in `plugin.json` with the configured values
(HTML-escaped) and adds them to the page head and the end of the body.

## Configuration

- **Enable Banner**: Toggle the banner on/off
- **Banner Message**: The text to display
- **Background Color**: Customize the background color
- **Text Color**: Customize the text color

## Version History

### 1.1.0
- Declarative `inject` templates replace `server.js`, for the Rust CMS

### 1.0.3
- Move the banner to a static position at the bottom of the page

### 1.0.0 (Initial Release)
- Basic banner functionality
- Customizable message
- Customizable colors
- Enable/disable toggle
