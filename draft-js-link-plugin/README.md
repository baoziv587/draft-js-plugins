# Draft.js Link Plugin

*This is a plugin for the `draft-js-plugins-editor`.*

This plugin allows you to add link entities via the [inline toolbar](https://www.draft-js-plugins.com/plugin/inline-toolbar). It also provides a decorator that formats the created entities.

## Usage

```js
import createLinkPlugin from 'draft-js-link-plugin';

const linkPlugin = createLinkPlugin();
```

### Importing the default styles

The plugin ships with a default styling available at this location in the installed package:
`node_modules/draft-js-link-plugin/lib/plugin.css`.

If you want to use the default styles, you can include this stylesheet. Otherwise you can supply your own styles via the `theme` config option.
